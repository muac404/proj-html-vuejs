<script>
export default {
  name: "AppOurTeam",
};
</script>
<template>
  <div class="row">
    <div class="col">
      <div class="team-card">
        <img src="../assets/h1-team-1a-700x700.jpg" alt="team-1" />
      </div>
    </div>
    <div class="col">
      <div class="team-card">
        <img src="../assets/h1-team-2a.jpg" alt="team-2" />
      </div>
    </div>
    <div class="col">
      <div class="team-card">
        <img src="../assets/h1-team-4a.jpg" alt="team-2" />
      </div>
    </div>
    <div class="col">
      <div class="team-card">
        <img src="../assets/h1-team-3a.jpg" alt="team-2" />
      </div>
    </div>
  </div>
</template>
<style scoped>
.row {
  display: flex;
}
.col {
  width: 25%;
}
.team-card img {
  width: 100%;
  cursor: pointer;
}
.team-card img:hover {
  width: 100%;
  opacity: 0.8;
}
</style>
