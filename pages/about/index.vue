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
        title: 'About',
        subTitle: 'Learn more about The Grid'
      }
    }
  }
</script>

<style lang="css">
</style>
