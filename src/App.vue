<template>
  <div id="app">
    <Header />
    <div class="container">
      <CardPosts />
    </div>
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import CardPosts from './components/CardPosts.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    CardPosts,
    Footer
  }
}
</script>

<style>
@import './assets/styles/bootstrap.css';
#app {
    height: 100vh;
    display: flex;
    flex-direction: column;
}
</style>
