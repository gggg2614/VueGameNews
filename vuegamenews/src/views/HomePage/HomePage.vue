<template>
  <div class="HomePage">
    <el-row :gutter="1">
      <el-col :span="8" > <MID1L></MID1L> </el-col>
      <el-col :span="8"> <MID1M></MID1M> </el-col>
      <el-col :span="8"> </el-col>
    </el-row>
  </div>
</template>

<script>
import MID1L from "./components/MID1L.vue";
import MID1M from "./components/MID1M.vue";
export default {
  methods: {},
  components: {
    MID1L,
    MID1M,
  },
  data() {
    return {};
  },
};
</script>

<style lang="scss" scoped>
.HomePage {
  
}

</style>
