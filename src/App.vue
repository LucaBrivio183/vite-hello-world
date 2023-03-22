<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
export default {
  components: {
    AppTitle,
    AppHero,
  }
}
</script>

<template>
  <div class="container">
    <AppTitle></AppTitle>
    <AppHero></AppHero>
  </div>
</template>

<style scoped>
.container {
  margin: 0 auto;
  max-width: 1000px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
</style>
