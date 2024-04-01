<template>
  <NavBar></NavBar>
  <div class="container">
    <div class="row">
      <div class="col-12 d-flex justify-content-center"></div>
      <HomepageCarousel></HomepageCarousel>
    </div>
    <div class="row text-start">
      <div class="col-md-2 col-6 border text-primary">
        Text 1
      </div>
      <div class="col-md-8 col-6 border">
        Text 2
      </div>
      <div class="col-md-2 col-12 border">
        Text 3
      </div>
    </div>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue';
import HomepageCarousel from "./components/HomepageCarousel.vue";

export default {
  name: 'App',
  components: {
    HomepageCarousel,
    NavBar
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
