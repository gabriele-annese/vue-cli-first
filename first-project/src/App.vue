<template>
  <div id="app">
      <Title />
      <Hero />
      <Hero2 />
  </div>
</template>

<script>
import Title from './components/Title.vue';
import Hero from './components/Hero.vue';
import Hero2 from './components/Hero2';
export default {
  name: 'App',
  components: {
    Title,
    Hero,
    Hero2
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffff;
  margin-top: 60px;
}
body{
  background-color: #313131;
}
</style>
