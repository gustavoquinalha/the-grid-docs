<template>
  <div id="app">
    <fullHeader/>
    <nuxt/>
  </div>
</template>

<script>
  import fullHeader from '@/components/fullHeader'
  export default {
    name: 'app',
    components: {
      fullHeader
    },
    mounted() {},
    data() {
      return {}
    }
  }
</script>

<style lang="scss">
  @import './assets/css/main.scss';
</style>
