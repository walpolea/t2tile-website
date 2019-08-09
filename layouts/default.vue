<template>
  <div>
    <nuxt />
  </div>
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
  color: #3bdaff;
  text-decoration: none;
  padding: 10px 30px;
}

.button--blue:hover {
  color: #fff;
  background-color: #3bdaff;
}
</style>
