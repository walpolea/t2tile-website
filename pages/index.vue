<template>
  <section class="container">
    <logo />
    <h1 class="title">
      The T2 Tile Project
    </h1>
    <h2 class="subtitle">
      Working for bigger and safer computing using living systems principles.
    </h2>

    <SiteNav />
    <article class="brief-overview">
      <div class="video-container">
        <iframe
          width="560"
          src="https://www.youtube.com/embed/jreRFxN6wuM"
          frameborder="0"
          allow="autoplay; encrypted-media"
          allowfullscreen
        ></iframe>
      </div>

      <p>
        <strong>
          The T2 Tile project is an attempt to build the world's first
          indefinitely scalable computational stack.
        </strong>
        First, we suspend the idea that we must be bound to an architecture
        based on correct and efficient deterministic hardware and software.
        Instead, much like the physical world around us, we look to robustness
        as a foundational requirement, building living systems as vessels for
        digital computation that is firstly robust, then as correct as possible,
        and finally, as efficient as necessary.
      </p>
    </article>
  </section>
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

<style lang="scss">
.container {
  margin: 110px auto;
  display: grid;
  grid-template-columns: 1fr;
  justify-content: center;
  align-items: center;
  text-align: center;

  img {
    margin: auto;
  }
}

.title {
  display: block;
  font-weight: 700;
  font-size: 70px;
  color: #222222;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 24px;
  color: #666666;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}

.brief-overview {
  background-color: white;
  padding: 40px;
  margin: 20px 0;
  border-radius: 1rem;

  p {
    color: #343434;
    text-align: left;
    line-height: 1.8rem;
    font-size: 1.2rem;
  }

  .video-container {
    position: relative;
    padding-bottom: 56.25%;
    padding-top: 30px;
    margin-bottom:1rem;
    height: 0;
    overflow: hidden;

  }

  .video-container iframe,
  .video-container object,
  .video-container embed {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
  }
}
</style>
