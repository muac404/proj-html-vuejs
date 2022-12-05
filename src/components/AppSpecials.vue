<script>
export default {
  name: "AppSpecials",
};
</script>
<template>
  <div class="container">
    <div class="left-section">
      <img src="../assets/h1-img-7n.png" alt="h1" />
    </div>
    <div class="right-section">
      <div class="specials-text">
        <h2>SPECIALS*</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container {
  display: flex;
}
.left-section {
  width: 50%;
  min-height: 800px;
  background-image: url("../assets/h1-img-4.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  display: flex;
  justify-content: center;
  align-items: center;
}

.right-section {
  width: 50%;
}

.specials-text {
  margin-left: 120px;
  margin-top: 120px;
}
p {
  color: grey;
  font-weight: 300;
}
</style>
