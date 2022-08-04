<template>
  <section class="main">
    <router-view :key="key"></router-view>
  </section>
</template>

<script>
export default {
  computed: {
    key () {
      return this.$route.pash
    }
  }
}
</script>

<style lang="scss">
</style>
