<template>
  <div class="home">
    <div class="hero is-black is-fullheight-with-navbar is-0-desktop-only">
      <div class="hero-body is-flex is-justify-content-center">
        <img alt="Vue logo" src="../assets/logo.png">
        <HelloWorld msg="Welcome to Your Vue.js App"/>
      </div>
    </div>
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
