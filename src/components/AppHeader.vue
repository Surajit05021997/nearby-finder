<template>
  <header>
    <div class="main-header">
      <div class="container">
        <img class="brand-logo" src="../assets/brand-logo.svg" alt="">
        <p class="brand-heading"><span>N</span>EARBY <span>F</span>INDER</p>
      </div>
    </div>
    <div class="hero-header">
      <div class="container">
        <h1 class="hero-header-text">Looking for places nearby? Look no further!
          Discover the best local businesses and services with our nearby finder tool.</h1>
        <img src="../assets/hero-header-image.jpg" alt="">
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'AppHeader',
};
</script>

<style scoped>
h1 {
  font-size: 3rem;
}
.main-header {
  background-color: #3730a3;
  color: #eef2ff;
  padding: 2rem;
}
.main-header > .container {
  display: flex;
  gap: .5rem;
}
.brand-heading {
  font-size: 2rem;
  letter-spacing: 2px;
}
.brand-heading > span {
  font-size: 3rem;
}
.hero-header {
  padding: 2rem;
}
.hero-header > .container {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
}
.hero-header-text {
  align-self: center;
}
</style>
