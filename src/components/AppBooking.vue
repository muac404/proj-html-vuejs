<script>
export default {
  name: "AppBooking",
};
</script>
<template>
  <section class="booking">
    <input type="text" placeholder="1 Person" />
    <i class="fa-solid fa-user-plus booking-icon"></i>
    <h2>FOR</h2>
    <input type="text" placeholder="11/29/2023" />
    <i class="fa-regular fa-calendar booking-icon"></i>
    <h2>AT</h2>
    <input type="text" placeholder="7:00 pm" />
    <i class="fa-solid fa-clock booking-icon"></i>
    <button>BOOK A TABLE</button>
  </section>
</template>

<style scoped>
.booking {
  padding-top: 100px;
  padding-bottom: 100px;
  background-image: url("../assets/h3-background-img-3.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  display: flex;
  justify-content: center;
  align-items: center;
}
input {
  margin: 15px;
  padding: 15px;
}
.booking-icon {
  color: #b7903c;
  position: relative;
  left: -50px;
}
h2 {
  color: white;
}
button {
  padding: 15px;
  color: white;
  background-color: #d2401e;
  border: none;
  cursor: pointer;
}

button:hover {
  background-color: black;
}
</style>
