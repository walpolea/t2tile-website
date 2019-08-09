<template>
  <header>
    <a href="/">
      <Logo />
    </a>
    <SiteNav />
  </header>
</template>

<script>
import Logo from "~/components/Logo.vue";
import SiteNav from "~/components/SiteNav.vue";

export default {
  components: { Logo, SiteNav }
};
</script>

<style lang="scss" scoped>
header {
  display: grid;
  grid-template-columns: 250px 1fr;
  gap: 1rem;
  align-items: end;
  justify-items: center;
  justify-content: center;
}

@media screen and (max-width: 500px) {
  header {
    grid-template-columns: 1fr;
  }
}
</style>



        