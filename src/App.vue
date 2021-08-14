<template>
  <navbar></navbar>
  <router-view/>
  <Footer></Footer>
</template>

<script>
import navbar from "./components/navbar";
import Footer from'./components/footer'
export default {
  components: {
    navbar,
    Footer
  }
}
</script>

<style lang="scss">
</style>
