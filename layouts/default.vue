<template>
  <div>
    <the-header />
    <nuxt />
  </div>
</template>

<script>
import theHeader from '@/components/theHeader'

export default {
  components: {
    theHeader
  }
}
</script>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
}
body {
  margin-top: 0;
}
</style>
