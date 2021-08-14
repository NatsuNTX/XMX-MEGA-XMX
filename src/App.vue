<template>
  <navbar></navbar>
  <router-view/>
</template>

<script>
import navbar from "./components/navbar";
export default {
  components: {
    navbar
  }
}
</script>

<style lang="scss">
</style>
