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
        <div class="overlay">
          <div class="team-information">
            <h4>MICHAEL JACKSON</h4>
            <h6>CEO & FOUNDER</h6>
            <ul class="social-icons">
              <li><i class="fa-brands fa-instagram"></i></li>
              <li><i class="fa-brands fa-twitter"></i></li>
              <li><i class="fa-brands fa-facebook"></i></li>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <div class="col">
      <div class="team-card">
        <img src="../assets/h1-team-2a.jpg" alt="team-2" />
        <div class="overlay">
          <div class="team-information">
            <h4>JANE MERCURY</h4>
            <h6>SOCIAL MEDIA MANAGER</h6>
            <ul class="social-icons">
              <li><i class="fa-brands fa-instagram"></i></li>
              <li><i class="fa-brands fa-twitter"></i></li>
              <li><i class="fa-brands fa-facebook"></i></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <div class="col">
      <div class="team-card">
        <img src="../assets/h1-team-4a.jpg" alt="team-2" />
        <div class="overlay">
          <div class="team-information">
            <h4>STEVEN JOBS</h4>
            <h6>MARKETING</h6>
            <ul class="social-icons">
              <li><i class="fa-brands fa-instagram"></i></li>
              <li><i class="fa-brands fa-twitter"></i></li>
              <li><i class="fa-brands fa-facebook"></i></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <div class="col">
      <div class="team-card">
        <img src="../assets/h1-team-3a.jpg" alt="team-2" />
        <div class="overlay">
          <div class="team-information">
            <h4>AMY WINEHOUSE</h4>
            <h6>WEB DEVELOPER</h6>
            <ul class="social-icons">
              <li><i class="fa-brands fa-instagram"></i></li>
              <li><i class="fa-brands fa-twitter"></i></li>
              <li><i class="fa-brands fa-facebook"></i></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
h6 {
  font-weight: 300;
  letter-spacing: 2px;
}
.row {
  display: flex;
}
.col {
  width: 25%;
}
.team-card {
  position: relative;
  cursor: pointer;
}

.social-icons {
  display: flex;
  justify-content: center;
  align-items: center;
}

.social-icons i {
  margin: 5px;
}
li {
  list-style: none;
}
.team-card img {
  width: 100%;
  display: block;
  cursor: pointer;
}
.overlay {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  height: 100%;
  width: 100%;
  opacity: 0;
  background-color: #d2401e;
}
.team-card:hover .overlay {
  opacity: 1;
}
.team-information {
  position: absolute;
  color: white;
  text-align: center;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
</style>
