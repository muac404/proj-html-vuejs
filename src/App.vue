<script>
import AppHeader from "./components/AppHeader.vue";
import AppHero from "./components/AppHero.vue";
import AppNav from "./components/AppNav.vue";
import AppSpecials from "./components/AppSpecials.vue";
import AppSlogan from "./components/AppSlogan.vue";
import AppQuote from "./components/AppQuote.vue";

export default {
  components: {
    AppHeader,
    AppHero,
    AppSpecials,
    AppNav,
    AppSlogan,
    AppQuote,
  },
};
</script>

<template>
  <AppHeader />
  <AppHero />
  <AppSlogan />
  <AppQuote />
  <AppSpecials />
</template>

<style scoped></style>
