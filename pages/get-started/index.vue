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
        title: 'Flexbox Grid',
        subTitle: 'Atomic design, bootstrap compatible, pure flexbox atomic design, pure flexbox.'
      }
    }
  }
</script>

<style lang="css">
</style>
