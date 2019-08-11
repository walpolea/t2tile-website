<template>
  <section id="people">
    <h1>PEOPLE</h1>
    <ul v-if="pageContent" class="people-list" v-html="pageContent"></ul>
  </section>
</template>

<script>
import marked from "marked";
import axios from "axios";

export default {
  layout: "subpage",
  data() {
    return {
      pageContent: undefined
    };
  },
  async mounted() {
    const md = await axios.get("/content/people.md");
    this.pageContent = marked(md.data);
  },
  methods: {
    convertToMarkdown(content) {
      return marked(content);
    }
  }
};
</script>

<style lang="scss">
h1 {
  margin: 20px 0;
}

ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

.people-list {
  margin-top: 40px;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));

  gap: 1rem;

  .person {
    font-size: 0.8rem;
  }
}
</style>
