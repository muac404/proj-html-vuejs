<script>
export default {
  name: "AppPizzaEvents",
};
</script>
<template>
  <div class="container">
    <section class="left-section">
      <div class="section-text">
        <h5 class="primary">MADE WITH LOVE</h5>
        <h2>DELISH PIZZA DEALS</h2>
      </div>

      <div class="event-card">
        <div class="day">
          <h2 class="primary">02</h2>
          <h3>NOV</h3>
        </div>
        <div class="event-details">
          <h2>TRADITIONAL NEAPOLITAN PIES IN KYOTO PIZZA MERCATO</h2>
          <h6 class="primary">
            <i class="fa-sharp fa-solid fa-location-dot"></i> 204. Piazzetta
            Tommaso
          </h6>
        </div>
      </div>

      <div class="event-card border">
        <div class="day">
          <h2 class="primary">03</h2>
          <h3>NOV</h3>
        </div>
        <div class="event-details">
          <h2>TERRAZZA PATIO DINING SPACE OPENING THIS WEEKEND</h2>
          <h6 class="primary">
            <i class="fa-sharp fa-solid fa-location-dot"></i> 208. Piazzetta
            Stefano
          </h6>
        </div>
      </div>

      <div class="event-card">
        <div class="day">
          <h2 class="primary">05</h2>
          <h3>NOV</h3>
        </div>
        <div class="event-details">
          <h2>SIENNA PRIVATE DINING ROOM WITH STEPHANE BRUN</h2>
          <h6 class="primary">
            <i class="fa-sharp fa-solid fa-location-dot"></i> 212. Piazzetta
            Tommaso
          </h6>
        </div>
      </div>
    </section>
    <section class="right-section">
      <img src="../assets/h3-img-5a.jpg" alt="5a" />
    </section>
  </div>
</template>

<style scoped>
.container {
  display: flex;
}

.left-section {
  background-color: #1a1a1a;
  width: 50%;

  padding-top: 100px;
  padding-right: 150px;
  padding-left: 150px;
  padding-bottom: 100px;
}
.section-text {
  margin-bottom: 20px;
}
h3,
h2 {
  color: white;
}

.day h2 {
  text-align: center;
  font-size: 32px;
  margin-bottom: 0;
}

.day h3 {
  text-align: center;
  margin-top: 0;
}

h6 {
  font-weight: 300;
  letter-spacing: 2px;
}

.primary {
  color: #ab4027;
}

.right-section {
  width: 50%;
}

.right-section img {
  width: 100%;
}

.event-card {
  display: flex;
  padding: 20px;
}

.day {
  margin-right: 20px;
}

.border {
  border-top: 2px dotted #b7903c;
  border-bottom: 2px dotted #b7903c;
}
</style>
