<template lang="html">
  <div class="menu container justify-content-between align-items-center bg-color">
    <div class="menu__logo margin-10">
      <span><router-link :to="{ path: '/'}">The Grid</router-link></span>
    </div>
    <ul class="menu__links container">
      <li class="margin-10" v-for="x in menuItems"><router-link :to="{ path: x.link }">{{x.name}}</router-link></li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      menuItems: [
        {name: 'Get Started', link: '/get-started'},
        {name: 'Documentation', link: '/documentation'},
        {name: 'Examples', link: '/examples'},
        {name: 'About', link: '/about'}
      ]
    }
  }
}
</script>

<style lang="scss" scoped>
  //@import 'assets/css/main'

  .menu {
    width: 100%;
    height: 60px;
    .menu__logo {
    }
    .menu__links {
      list-style: none;
    }
  }
</style>
