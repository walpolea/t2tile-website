<template>
  <main>
    <nuxt />
  </main>
</template>

<style>
@import url("https://rsms.me/inter/inter.css");
html {
  font-family: "Inter", sans-serif;
}
@supports (font-variation-settings: normal) {
  html {
    font-family: "Inter var", sans-serif;
  }
}

html {
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

body {
  background-color: #f3f4e4;
}

.button--blue {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3bdaff;
  background-color: #f9f9f2;
  color: #3bdaff;
  text-decoration: none;
  padding: 4px 10px;
  margin: 4px 2px;
}

.button--blue:hover {
  color: #fff;
  background-color: #3bdaff;
}

main {
  padding: 10px;
  max-width: 900px;
  margin: 0 auto;
}
</style>
