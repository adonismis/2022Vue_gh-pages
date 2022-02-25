<template>
  <div class="home">
    Home
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  // components: {
  //   HelloWorld
  // },
  mounted () {
    console.log(this.$http.get)
    alert('test')
  }
}
</script>
