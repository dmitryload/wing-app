<template>
  <Nuxt/>
</template>

<script>
export default {}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500&display=swap');

body {
  width: 100%;
  margin: 0;
  font-family: 'Inter', sans-serif;
  font-size: 16px;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #0a0a0a;
  background: #f5f5f5;
  line-height: 1;
}

* {
  padding: 0;
  margin: 0;
  border: 0;
}

:focus, :active, :hover {
  outline: none;
}

a, a:visited, a:focus, a:active, a:hover {
  outline: none;
  text-decoration: none;
}


input, button, textarea {
  font-family: inherit;
}

button {
  cursor: pointer;
  background-color: rgba(255, 255, 255, 0);
}

ol, ul, li {
  list-style: none;
}

img {
  vertical-align: top;
}

h1, h2, h3, h4, h5, h6 {
  font-size: inherit;
  font-weight: inherit;
}

table,
thead,
tbody,
tfoot,
tr,
th,
td {
  display: block;
  width: auto;
  height: auto;
  margin: 0;
  padding: 0;
  border: none;
  border-collapse: inherit;
  border-spacing: 0;
  border-color: inherit;
  vertical-align: inherit;
  text-align: left;
  font-weight: inherit;
  -webkit-border-horizontal-spacing: 0;
  -webkit-border-vertical-spacing: 0;
}

th, td {
  display: inline;
}
@media(max-width: 1200px) {
  body {
    font-size: 14px;
  }
}
</style>