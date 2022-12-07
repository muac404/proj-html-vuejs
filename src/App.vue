<script>
import AppHeader from "./components/AppHeader.vue";
import AppHero from "./components/AppHero.vue";
import AppNav from "./components/AppNav.vue";
import AppSpecials from "./components/AppSpecials.vue";
import AppSlogan from "./components/AppSlogan.vue";
import AppQuote from "./components/AppQuote.vue";
import AppBuildPizza from "./components/AppBuildPizza.vue";
import AppOurTeam from "./components/AppOurTeam.vue";
import AppClients from "./components/AppClients.vue";
import AppFlavors from "./components/AppFlavors.vue";
import AppPizzaEvents from "./components/AppPizzaEvents.vue";

export default {
  components: {
    AppHeader,
    AppHero,
    AppSpecials,
    AppNav,
    AppSlogan,
    AppQuote,
    AppBuildPizza,
    AppOurTeam,
    AppClients,
    AppFlavors,
    AppPizzaEvents,
  },
};
</script>

<template>
  <AppHeader />
  <AppHero />
  <AppSlogan />
  <AppQuote />
  <AppSpecials />
  <AppBuildPizza />
  <AppOurTeam />
  <AppClients />
  <AppFlavors />
  <AppPizzaEvents />
</template>

<style scoped></style>
