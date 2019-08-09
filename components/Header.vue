<template>
  <header>
    <a href="/">
      <Logo />
    </a>
    <nav>
      <ul>
        <li><a href="/overview" class="button--blue">Overview</a></li>
        <li><a href="/people" class="button--blue">People</a></li>
        <li>
          <a
            href="https://www.youtube.com/channel/UC1M91QuLZfCzHjBMEKvIc-A"
            target="_blank"
            class="button--blue"
            >T2sday Updates</a
          >
        </li>
        <li>
          <a
            href="https://github.com/DaveAckley/T2-12"
            target="_blank"
            class="button--blue"
          >
            GitHub
          </a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
import Logo from "~/components/Logo.vue";
export default {
  components: { Logo }
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
ul {
  margin: 0;
  padding: 0;
  list-style: none;
}

li {
  display: inline-block;
}

@media screen and (max-width: 500px) {
  header {
    grid-template-columns: 1fr;
  }
}
</style>



        