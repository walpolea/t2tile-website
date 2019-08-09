<template>
  <div class="container">
    <div>
      <logo />
      <h1 class="title">
        The T2 Tile Project
      </h1>
      <h2 class="subtitle">
        Working for bigger and safer computing using living systems principles.
      </h2>
      <SiteNav />
    </div>
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";
import SiteNav from "~/components/SiteNav.vue";

export default {
  components: {
    Logo,
    SiteNav
  }
};
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  display: block;
  font-weight: 700;
  font-size: 80px;
  color: #222222;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 36px;
  color: #666666;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
