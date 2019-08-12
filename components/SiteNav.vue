<template>
  <nav>
    <ul>
      <!-- <li><a href="/overview" class="button--blue">Overview</a></li>
      <li><a href="/people" class="button--blue">People</a></li> -->
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
      <li>
        <a href="https://gitter.im/t2tile/" target="_blank" class="button--blue"
          >Chat Room</a
        >
      </li>
    </ul>
  </nav>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
ul {
  margin: 0;
  padding: 0;
  list-style: none;
  text-align: center;

  li {
    display: inline-block;
  }
}

@media screen and (max-width: 500px) {
  ul {
    display: flex;
    flex-direction: column;
  }
  li {
    a {
      width: 100%;
    }
  }
}
</style>
