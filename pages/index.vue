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
      <p>
      stuff stuff abstract stuff
      </p>
      <div class="links">
        <a href="/overview" class="button--blue">Overview</a>
        <a href="/people" class="button--blue">People</a>
        <a
          href="https://www.youtube.com/channel/UC1M91QuLZfCzHjBMEKvIc-A"
          target="_blank"
          class="button--blue"
        >
          T2sday Updates
        </a>
        <a
          href="https://github.com/DaveAckley/T2-12"
          target="_blank"
          class="button--blue"
        >
          GitHub
        </a>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from "~/components/Logo.vue";

export default {
  components: {
    Logo
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
