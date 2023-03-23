<script>
import "@fontsource/montserrat";
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";

export default {
  data() {
    return {

    }
  },

  components: {
    AppTitle,
    AppHero,
  },
}
</script>
<template>
  <AppHero></AppHero>
  <AppTitle></AppTitle>
</template>
<style>
body {
  font-family: "Montserrat";
}
</style>