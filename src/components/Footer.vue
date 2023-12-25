<template>
  <footer>
    <div class="footer">
      <div class="footer-logo">
        <img src="../assets/images/eu.jpg" alt="Owner" class="dono"/>
      </div>
      <div class="footer-social">
        <a href="www.linkedin.com/in/luiz-fernando-blume-jacinto-532447280" target="_blank">
          <div class="icons-background">
            <img src="../assets/images/linkedin-icon.png" alt="linkedin" class="icons" /></div
        ></a>
        <a href="https://www.instagram.com/blume.047" target="_blank">
          <div class="icons-background">
            <img src="../assets/images/instagram-icon.png" alt="instagram" class="icons" /></div
        ></a>
        <a href="https://www.github.com/LuizBlume" target="_blank">
          <div class="icons-background">
            <img src="../assets/images/github-icon.png" alt="github" class="icons" /></div
        ></a>
      </div>
      <div class="footer-links">
        <a href="#">About</a>
        <a href="#">Contact</a>
        <a href="#">Terms of Use</a>
        <a href="#">Privacy Policy</a>
      </div>
    </div>
  </footer>
</template>
<style scoped>
.footer {
  background: linear-gradient(#141414 0%, #8d8d8d 100%);
  padding: 20px;
  backdrop-filter: blur(5px);
  color: white;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.icons {
  width: 50px;
  height: 50px;
}
.footer-social {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.icons-background {
  background-color: rgba(192, 192, 192, 0.7);
  border-radius: 50%;
  width: 85px;
  height: 85px;
  padding: 5px;
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 0 10px;
  transition: background-color 0.5s, box-shadow 0.5s, transform 0.5s;
}
.icons-background:hover {
  background-color: rgba(192, 192, 192, 0.9);
  box-shadow: 1px 1px 10px 10px #900ecd;
  transition: 1s;
  transform: scale(1.1);
}
.dono {
    width: 170px;
    height: 230px;
    border-radius: 50%;
    margin: 0 10px;
}
</style>
<script setup>
</script>