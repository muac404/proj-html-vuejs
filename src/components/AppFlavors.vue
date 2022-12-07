<script>
export default {
  name: "AppFlavors",
};
</script>
<template>
  <div class="flavors-text">
    <h5 class="primary">CHOOSE YOUR FLAVOR</h5>
    <h2 class="m-5">THE BEST PIZZA MENU IN TOWN</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Praesentium
      cupiditate ea ab officiis excepturi. Atque eum explicabo expedita illum
      officia quis, suscipit beatae accusamus repellat, alias, soluta hic magni
      et.
    </p>
  </div>
  <div class="pizza-row">
    <div class="pizza-card">
      <img src="../assets/h3-product-img-2a-150x150.png" alt="fiori-di-zucca" />

      <h5 class="text-center gold">FIORI DI ZUCCA</h5>
      <h5 class="text-center primary">$7.00-$50.00</h5>
    </div>

    <div class="pizza-card">
      <img src="../assets/h3-product-img-3a-150x150.png" alt="valdostana" />

      <h5 class="text-center gold">VALDOSTANA</h5>
      <h5 class="text-center primary">$55.00</h5>
    </div>

    <div class="pizza-card">
      <img src="../assets/h3-product-img-4a-150x150.png" alt="tartufata" />

      <h5 class="text-center gold">PIZZA TARTUFATA</h5>
      <h5 class="text-center primary">$45.00</h5>
    </div>

    <div class="pizza-card">
      <img src="../assets/h3-product-img-5a-150x150.png" alt="valdostana" />

      <h5 class="text-center gold">VALDOSTANA</h5>
      <h5 class="text-center primary">$55.00</h5>
    </div>

    <div class="pizza-card">
      <img src="../assets/h3-product-img-3a-150x150.png" alt="bismarck" />

      <h5 class="text-center gold">BISMARCK</h5>
      <h5 class="text-center primary">$30.00</h5>
    </div>

    <div class="pizza-card">
      <img src="../assets/h3-product-img-4a-150x150.png" alt="tartufata" />

      <h5 class="text-center gold">PIZZA TARTUFATA</h5>
      <h5 class="text-center primary">$45.00</h5>
    </div>
  </div>
</template>

<style scoped>
.flavors-text {
  width: 700px;
  margin: auto;
  text-align: center;
  margin-top: 40px;
}

.text-center {
  text-align: center;
}

.pizza-row {
  display: flex;
  justify-content: center;
  margin-top: 60px;
  margin-bottom: 60px;
}

.pizza-card {
  margin: 40px;
  cursor: pointer;
}

.pizza-card:hover {
  scale: 1.2;
}

.gold {
  color: #b7903c;
}

.primary {
  color: #d3401e;
}
.m-5 {
  margin-top: 5px;
  margin-bottom: 5px;
}
</style>
