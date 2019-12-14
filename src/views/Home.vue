<template>
  <div class="home">
    <!--start-->
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <!--end-->
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';
// import components

export default {
  name: 'home',
  components: {
    HelloWorld,
    // components
  }
}
</script>
