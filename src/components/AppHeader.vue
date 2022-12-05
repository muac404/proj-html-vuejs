<script>
import AppLogo from "./AppLogo.vue";
import AppNav from "./AppNav.vue";
export default {
  name: "AppHeader",
  components: {
    AppLogo,
    AppNav,
  },
};
</script>
<template>
  <div class="header">
    <AppNav />
    <div class="hero-img">
      <img src="../assets/h3-rev-img-6.png" alt="urban-taste" />
    </div>
  </div>
</template>

<style scoped>
.header {
  background-color: #181818;
  padding: 20px;
  height: 700px;
}
.hero-img {
  display: flex;
  justify-content: center;
  background-image: url("../assets/h3-rev-img-5.png");
  background-size: contain;
  background-repeat: no-repeat;

  background-position: center;
}
</style>
