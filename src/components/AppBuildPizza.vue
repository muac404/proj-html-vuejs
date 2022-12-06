<script>
export default {
  name: "AppBuildPizza",
};
</script>
<template>
  <section class="build-your-pizza">
    <div class="build-pizza-text">
      <h2>GO AHEAD AND BUILD YOUR OWN PIZZA WE WON'T JUDGE!</h2>
    </div>
  </section>
</template>
<style scoped>
.build-your-pizza {
  background-image: url("../assets/h3-background-img.jpg");
  background-size: cover;
  background-position: center;
  border-top: 5px solid white;
  border-bottom: 5px solid white;
}
.build-pizza-text {
  max-width: 25%;
  font-size: 40px;
  line-height: 55px;
  padding-top: 100px;
  padding-bottom: 100px;
  color: white;
  margin-left: 25%;
}
</style>
