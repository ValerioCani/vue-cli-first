<template>
  <div id="app">
    <MyTitle/>
    <HeroSection/>
  </div>
</template>

<script>
import MyTitle from '@/components/MyTitle.vue';
import HeroSection from '@/components/Hero.vue';
export default {
  name: 'App',
  components: {
    MyTitle,
    HeroSection
}
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
