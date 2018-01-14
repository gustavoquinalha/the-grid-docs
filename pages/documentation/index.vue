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
        title: 'Documentation',
        subTitle: 'See the specifiations for The Grid'
      }
    }
  }
</script>

<style lang="css">
</style>
