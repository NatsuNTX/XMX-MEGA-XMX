<template>
  <div class="home">
    <div class="hero is-black is-fullheight-with-navbar is-0-desktop-only">
      <div class="hero-body is-flex is-justify-content-center">
        <!-- Content of the Pages -->
        <content class="is-flex">
          <div class="image is-128x128" aria-label="logo">
            <img alt="Owner" src="../assets/owner.png">
          </div>
          <div class="ml-2 mt-5" aria-label="MainDescription">
            <pageTitle
                arial-label="title"
                class="title">
              Welcome to Project NTX8831MGA
            </pageTitle>
            <pageDescription
                class="subtitle">
              <p>Just a Simple Website from XMX-MEGA-XMX</p>
            </pageDescription>
          </div>
        </content>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import settings from '../config/config.json'

export default {
  name: 'Home',
  components: {
    HelloWorld
  },
  data() {
    return {
      homeBackground: settings.homeBackgroundImage
    }
  }
}
</script>
<style>
#bg {
  z-index: -5;
  object-fit: cover;
}
</style>
