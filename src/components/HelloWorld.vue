<template>

    <h1>{{ msg }}</h1>
  

    <div class="bg-gray-200 p-4">
      <h1 class="text-xl font-bold text-blue-500">Hello, Tailwind!</h1>
      <p class="text-gray-700 mt-2">This is a Tailwind CSS example.</p>
    </div>



</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}



</style>
