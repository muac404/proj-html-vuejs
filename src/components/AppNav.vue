<script>
import AppLogo from "./AppLogo.vue";

export default {
  name: "AppNav",
  components: { AppLogo },
};
</script>
<template>
  <div class="container">
    <nav class="main-nav">
      <ul class="left-nav">
        <li><button>ORDER ONLINE</button></li>
      </ul>
      <ul class="center-nav">
        <li>HOME</li>
        <li>PAGES</li>
        <li>MENU</li>
        <li><AppLogo class="logo" /></li>
        <li>EVENT</li>
        <li>BLOG</li>
        <li>LANDING</li>
      </ul>
      <ul class="right-nav">
        <li>CART</li>
        <li>SEARCH</li>
      </ul>
    </nav>
  </div>
</template>

<style scoped>
.container {
  max-width: 1200px;
  margin: auto;
}

.logo {
  max-height: 120px;
}
li {
  list-style: none;
  cursor: pointer;
  margin: 5px;
  color: white;
}
.main-nav {
  display: flex;
  justify-content: center;
  margin-bottom: 40px;
}
.center-nav {
  display: flex;
  align-items: center;
}

.left-nav {
  display: flex;
  align-items: center;
}

.right-nav {
  display: flex;
  align-items: center;
}
</style>
