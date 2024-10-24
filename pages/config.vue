<template>
  <div>
    <config />
  </div>
</template>

<script>
import Config from '~/components/Config'
export default {
  components: {
    Config
  },
  head() {
    return {
      title: 'ESP32 Energy Config tool built w/ Nuxt.js'
    }
  }
}
</script>
