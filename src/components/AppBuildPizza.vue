<script>
export default {
  name: "AppBuildPizza",
};
</script>
<template>
  <section class="build-your-pizza">
    <div class="build-pizza-text">
      <h2>GO AHEAD AND BUILD YOUR OWN PIZZA WE WON'T JUDGE!</h2>
      <div class="img-cut">
        <div class="cut-up"></div>
        <div class="cut-center"></div>
        <div class="cut-bottom"></div>
      </div>
    </div>
  </section>
</template>
<style scoped>
.build-your-pizza {
  background-image: url("../assets/h3-background-img-cut.png");
  background-size: cover;
  height: 800px;
  background-position: center;
  border-top: 5px solid white;
  border-bottom: 5px solid white;
}
.build-pizza-text {
  max-width: 25%;
  font-size: 40px;
  line-height: 55px;
  padding-top: 180px;
  padding-bottom: 100px;
  color: white;
  margin-left: 25%;
}
</style>
