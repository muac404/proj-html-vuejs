<script>
import AppHeader from "./components/AppHeader.vue";
import AppHero from "./components/AppHero.vue";
import AppNav from "./components/AppNav.vue";
import AppSpecials from "./components/AppSpecials.vue";

export default {
  components: {
    AppHeader,
    AppHero,
    AppSpecials,
    AppNav,
  },
};
</script>

<template>
  <AppHeader />

  <AppHero />
  <AppSpecials />
</template>

<style scoped></style>
