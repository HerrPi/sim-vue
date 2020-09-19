<template>
  <div class="home">
    <img id="logo" alt="Sim logo" src="../assets/simlogo.png">
    <HelloWorld msg="Eine Testnachricht..."/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>

<style scoped>
#logo {
  height: auto;
  width: 10rem;
}
</style>