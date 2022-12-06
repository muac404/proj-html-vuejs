<script>
export default {
  name: "AppSlogan",
};
</script>
<template>
  <div class="row">
    <div class="col">
      <img src="../assets/h3-img-1.jpg" alt="slogan-1" />
    </div>
    <div class="col">
      <img src="../assets/h3-img-2.jpg" alt="slogan-1" />
    </div>
    <div class="col">
      <img src="../assets/h3-img-3.jpg" alt="slogan-1" />
    </div>
    <div class="col">
      <img src="../assets/h3-img-4.jpg" alt="slogan-1" />
    </div>
  </div>
</template>
<style scoped>
.row {
  display: flex;
}

.col {
  width: 25%;
  border: 5px solid white;
}

.col img {
  width: 100%;
  display: block;
}
</style>
