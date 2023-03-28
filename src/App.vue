<template>
  <app-header />
  <app-search-panel />
</template>

<script>
import AppHeader from './components/AppHeader.vue';
import AppSearchPanel from './components/AppSearchPanel.vue';

export default {
  name: 'App',
  components: {
    AppHeader,
    AppSearchPanel,
  },
};
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Rubik:wght@400;500;600;700&display=swap');

*, *::before, *::after {
  box-sizing: border-box;
}

* {
  margin: 0;
  padding: 0;
  font: inherit;
}

html, body {
  height: 100%;
}

body {
  font-family: 'Rubik', sans-serif;
}

img, picture, svg, canvas {
  display: block;
  max-width: 100%;
}

#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.container {
  max-width: 87.5rem;
  margin-inline: auto;
}
</style>
