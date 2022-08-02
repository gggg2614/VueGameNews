<template>
  <div class="index">
    <el-container>
      <el-header>
        <Nav></Nav>
      </el-header>
      <el-main>
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
}
</style>
