<template>
  <div class="HomePage">
    <div v-for="(item, index) in a" :key="index">{{ a }} + {{index}}</div>
  </div>
</template>

<script>
export default {
  methods: {},
  data() {
    let a = [];
    for (let i = 0; i < 50; i++) {
      a.push(i);
    }
    return {
      a,
    };
  },
};
</script>

<style lang="scss" scoped>
.HomePage {
  color: $light-blue;
}
</style>
