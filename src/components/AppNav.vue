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
        <li><i class="fa-light fa-mustache"></i> HOME</li>
        <li>PAGES</li>
        <li>MENU</li>
        <li><AppLogo class="logo" /></li>
        <li>EVENT</li>
        <li>BLOG</li>
        <li>LANDING</li>
      </ul>
      <ul class="right-nav">
        <li><i class="fa-solid fa-cart-shopping"></i> CART</li>
        <li><i class="fa-solid fa-magnifying-glass"></i> SEARCH</li>
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
  margin-left: 15px;
  margin-right: 15px;
  color: white;
}
.main-nav {
  display: flex;
  justify-content: space-between;
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

.right-nav i {
  margin-right: 5px;
}

button {
  background-color: #d2401e;
  color: white;
  padding: 10px 20px;
  border: none;
  cursor: pointer;
}

button:hover {
  background-color: black;
}
</style>
