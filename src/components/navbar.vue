<template>
  <div class="navbar is-desktop is-black" id="navbar">
    <div class="navbar-menu is-justify-content-center">
      <router-link class="navbar-item has-text-white has-text-weight-bold" to="/">Home</router-link>
      <span style="background-color: white; width: 2px; height: 2.0rem; margin-top: 0.55rem" aria-label="border"></span>
      <router-link class="navbar-item has-text-white has-text-weight-bold" to="/about">About</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "navbar"
}
</script>

<style scoped>

</style>