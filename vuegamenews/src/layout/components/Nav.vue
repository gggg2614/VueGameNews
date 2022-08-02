<template>
  <div class="nav">
    <Header class="header"></Header>
    <TopNav class="topnav"></TopNav>
  </div>
</template>

<script>
import Header from './Header/Header.vue'
import TopNav from './Header/TopNav.vue'
export default {
  components: {
    Header,
    TopNav
  }
}
</script>
<style lang="scss" scoped>
.nav {
  height: 70px;
  .header{
    background: $hbgc;
    color: rgb(223, 221, 221);
    overflow: hidden;
    position: relative;
    box-shadow: 0 1px 4px rgba(0,21,41,.08);
  }
  }
</style>
