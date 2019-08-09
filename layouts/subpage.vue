<template>
  <main>
    <Header />
    <nuxt />
  </main>
</template>

<script>
import Header from "~/components/Header.vue";
export default {
  components: { Header }
};
</script>

<style lang="scss" scoped>
main {
  max-width: 900px;
  margin: 0 auto;
  margin-top: 20px;
}
</style>
