<template>
<div class="navbar is-fixed-bottom is-black is-flex is-justify-content-center">
  <p class="has-text-white">{{footer}}</p>
</div>
</template>

<script>
import settings from '../config/config.json'
export default {
  name: "footer",
  data() {
    return {
      footer: settings.footer
    }
  }
}
</script>

<style scoped>

</style>