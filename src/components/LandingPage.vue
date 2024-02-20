<template>
  
    <site-header/>

    <h1>{{ msg }}</h1>
  
    <section id="main-landing" class="p-3">

      <div class="p-2">
        <h1>BookHarbor</h1>
        <h2> Navigating your literary journey with every page</h2>
      </div>
      
    </section>


</template>

<script>

// Import header and footer

import SiteHeader from './SiteHeader.vue';

export default {
  name: 'HelloWorld',
  components:{
    SiteHeader,
  },
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>




</style>
