<template>
  <div class="mid1l">
    <div class="carouse">
      <el-carousel indicator-position="outside">
        <el-carousel-item v-for="item in 4" :key="item">
          <h3>{{ item }}</h3>
        </el-carousel-item>
      </el-carousel>
      <div class="mid1title">
        <el-row :gutter="20">
          <el-col :span="12"> 杂谈趣闻 </el-col>
          <el-col :span="12">
            <a href="">more</a>
          </el-col>
        </el-row>
      </div>
      <div class="mid1img">
        <el-row :gutter="20">
          <el-col :span="8"
            ><img src="@/assets/logo/logo.jpg" alt="" srcset=""
          /></el-col>
          <el-col :span="8"
            ><img src="@/assets/logo/logo.jpg" alt="" srcset=""
          /></el-col>
          <el-col :span="8"
            ><img src="@/assets/logo/logo.jpg" alt="" srcset=""
          /></el-col>
        </el-row>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>

<style lang="scss" scoped>
.el-carousel__item h3 {
  color: #5d5e61;
  font-size: 18px;
  opacity: 0.75;
  line-height: 300px;
  margin: 0;
}
.el-carousel__item:nth-child(2n) {
  background-color: #99a9bf;
}

.el-carousel__item:nth-child(2n + 1) {
  background-color: #d3dce6;
}
img {
  height: 50px;
}
.mid1l {
  float: left;
  height: auto;
}
</style>