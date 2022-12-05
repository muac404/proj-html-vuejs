<script>
export default {
  name: "AppQuote",
};
</script>
<template>
  <div class="container">
    <h1 class="quote-icon"><i class="fa-sharp fa-solid fa-quote-left"></i></h1>
    <div class="quote">
      <h2>
        "FORGET THE TRENY PIZZA SHOPS, THIS HIDDEN SPOT MAKES THE BEST NEW
        YORK-STYLE PIZZA SLICE IN NAPLES"
      </h2>
      <h5>WASHINGTON POST 2018</h5>
    </div>
  </div>
</template>
<style scoped>
.container {
  padding-top: 100px;
  padding-bottom: 100px;
  background-image: url("../assets/h3-testimonials-bckgrnd.jpg");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}
.quote-icon {
  color: #b7903c;
  font-size: 72px;
  text-align: center;
}
.quote {
  max-width: 800px;
  margin: auto;
  text-align: center;
  letter-spacing: 0.2rem;
}
h5 {
  color: #d2401e;
}
</style>
