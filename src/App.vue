<template>
  <div class="container">
    <AppHero/>
    <AppTitle />
  </div>
</template>

<script>
import AppHero from './components/AppHero.vue';
import AppTitle from './components/AppTitle.vue';
export default {
  components: {
    AppHero,
    AppTitle,
  }
}
</script>

<style lang="scss" scoped></style>