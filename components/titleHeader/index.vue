<template>
  <div class="">
    <div class="header container column align-center bg-color">
      <h1 class="header__title">{{title}}</h1>
      <p class="header__sub-title">{{subTitle}}</p>
    </div>

  </div>
</template>

<script>
  export default {
    components: {
    },
    props: {
      title: {
        type: String
      },
      subTitle: {
        type: String
      }
    },
    data() {
      return {

      }
    }
  }
</script>

<style lang="scss" scoped>
  .container {
    height: calc(100vh - 60px);
  }
</style>
