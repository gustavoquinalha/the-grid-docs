<template lang="html">
  <div class="">
    <titleHeader :title="title" :subTitle="subTitle"/>
  </div>
</template>

<script>
  import titleHeader from '@/components/titleHeader'

  export default {
    components: {
      titleHeader
    },
    data() {
      return {
        title: 'Examples',
        subTitle: 'Lives examples from The Grid'
      }
    }
  }
</script>

<style lang="css">
</style>
