<template>
  <div id="app">
    <Navigation></Navigation>
    <SecondNavigation></SecondNavigation>
    <div class="container">
      <router-view />
    </div>
    <FooterComponent></FooterComponent>
  </div>
</template>

<script>
import Navigation from './components/Navigation.vue';
import SecondNavigation from './components/SecondNavigation.vue'
import FooterComponent from './components/FooterComponent.vue'

export default {
  name: 'app',
  components: {
    Navigation,
    SecondNavigation,
    FooterComponent
}
}

</script>

<style>
#app {
  font-family: 'Roboto', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  background-color: #171717;
  min-height: 100vh;
}

.container {
  margin: 0 auto;
  padding-top: 10px;
  max-width: 1280px;
  width: 70%;
}

</style>
