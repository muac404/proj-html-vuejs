<script>
export default {
  name: "AppClients",
};
</script>
<template>
  <section class="our-team">
    <div class="container">
      <div class="partner-card">
        <img src="../assets/h1-clients-img-4.png" alt="clients-1" />
      </div>
      <div class="partner-card">
        <img src="../assets/h1-clients-img-3.png" alt="clients-1" />
      </div>
      <div class="partner-card">
        <img src="../assets/h1-clients-img-1.png" alt="clients-1" />
      </div>
      <div class="partner-card">
        <img src="../assets/h1-clients-img-2.png" alt="clients-1" />
      </div>
      <div class="partner-card">
        <img src="../assets/h1-clients-img-5.png" alt="clients-1" />
      </div>
    </div>
  </section>
</template>

<style scoped>
.our-team {
  background-color: #f7f7f2;
}
.container {
  max-width: 1000px;

  margin: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  padding-top: 80px;
  padding-bottom: 80px;
}

.partner-card img {
  width: 100%;
  cursor: pointer;
}

.partner-card img:hover {
  scale: 1.2;
}
</style>
