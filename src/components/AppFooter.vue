<script>
export default {
  name: "AppFooter",
};
</script>
<template>
  <section class="container">
    <div class="left-section">
      <div class="restaurants">
        <h3 class="gold">FIND OUR RESTAURANTS</h3>

        <div class="restaurant">
          <div>1614 E. Bell Rd #104.</div>
          <div>Salerno, AZ 85022</div>
          <div>(602) 867-1010</div>
        </div>

        <div class="restaurant">
          <div>204 E. Pizzetta Tommaso</div>
          <div>Sorrento, AZ 85022</div>
          <div>(359) 867-1010</div>
        </div>

        <div class="restaurant">
          <div>Viale Puglia 54</div>
          <div>Torre Del Greco, AZ 85022</div>
          <div>(359) 867-1010</div>
        </div>
      </div>
      <div class="open-hour">
        <h4 class="gold">WORKING HOURS</h4>
        <div class="monday m-10">
          <h5 class="gold">MONDAY</h5>
          <div class="primary">Kitchen Closed</div>
        </div>
        <div class="until-friday m-10">
          <h5 class="gold">TUESDAY UNTIL FRIDAY</h5>
          <div>9:00 - 22:00</div>
        </div>
        <div class="saturday m-10">
          <h5 class="gold">SATURDAY <span class="primary">*</span></h5>
          <div>Saturday 11 am to midnight</div>
        </div>
        <div class="sunday m-10">
          <h5 class="gold">SUNDAY</h5>
          <div>9:00 - 22:00</div>
        </div>
      </div>
      <div class="footer-slogan">
        <h2>
          THE DON PEPPE CREW FIRST AND FOREMOST VALUES AN AUTHENTIC, WELL BAKED
          SLICE OF PIZZA.
        </h2>
      </div>
    </div>
    <div class="right-section"></div>
  </section>
</template>

<style scoped>
.container {
  display: flex;
  height: 600px;
}

.left-section {
  height: 600px;
  width: 60%;
  display: flex;
  justify-content: space-between;
  background-color: #1b1b1b;
  padding: 40px;
  color: white;
}

.restaurant {
  margin-top: 15px;
  margin-bottom: 15px;
}

.m-10 {
  margin-top: 20px;
  margin-bottom: 20px;
}

.gold {
  color: #b7903c;
}

.primary {
  color: #d2401e;
}
.footer-slogan {
  width: 33%;
}
.right-section {
  height: 600px;
  width: 40%;
  background-image: url("../assets/footer-img-1.jpg");
  background-size: cover;
}
.right-section img {
  width: 600px;
}
</style>
