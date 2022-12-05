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
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Lorem ipsum
          dolor sit amet, consectetur adipisicing elit.
        </p>

        <div class="combo-card">
          <div class="combo-price">
            <h3>$10</h3>
          </div>

          <div class="combo-text">
            <h3>COMBO PICCOLO</h3>
            <p>
              <small
                >Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                Impedit inventore at rerum incidunt voluptatem
              </small>
            </p>
          </div>
        </div>
        <div class="combo-card">
          <div class="combo-price">
            <h3>$20</h3>
          </div>

          <div class="combo-text">
            <h3>COMBO MEDIO</h3>
            <p>
              <small
                >Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                Impedit inventore at rerum incidunt voluptatem
              </small>
            </p>
          </div>
        </div>
        <div class="combo-card">
          <div class="combo-price">
            <h3>$30</h3>
          </div>

          <div class="combo-text">
            <h3>COMBO GRANDE</h3>
            <p>
              <small
                >Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                Impedit inventore at rerum incidunt voluptatem
              </small>
            </p>
          </div>
        </div>
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
  max-width: 400px;
}
p {
  color: grey;
  font-weight: 300;
}

.combo-card {
  display: flex;
  margin-top: 20px;
}

.combo-price {
  color: #d2401e;
  margin-right: 10px;
}
</style>
