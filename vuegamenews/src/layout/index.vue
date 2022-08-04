<template>
  <div class="index">
    <el-container>
      <el-header class="header">
        <Nav></Nav>
      </el-header>
      <el-main class="main">
        <Main></Main>
      </el-main>
      <el-footer>
        <Bottom></Bottom>
      </el-footer>
    </el-container>
  </div>
</template>

<script>
import { Nav, Bottom, Main } from './components'
export default {
  components: {
    Nav,
    Bottom,
    Main
  }
}
</script>
<style lang="scss">
.index{
  text-align: center;
  background-color: $bgc;
  a{
    text-decoration: none;
  }

}
  .main{
    background-color: #f2f2f3;
    margin: 0 auto;
    padding: 10px 20px 0;
    width: auto
  }
.header{
}
</style>
