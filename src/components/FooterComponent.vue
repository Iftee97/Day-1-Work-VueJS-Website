<template>
  <div class="container-fluid footer-nav">
    <div class="foooter-links">
      <ul>
        <li>Home</li>
        <li>About</li>
      </ul>

      <img src="../assets/logo2.png" alt="logo-2" class="logo" />

      <ul>
        <li>Service</li>
        <li>Blog</li>
      </ul>
    </div>

    <hr class="footer-horizontal-rule" />

    <div class="social-icons">
      <i class="fa-brands fa-facebook"></i>
      <i class="fa-brands fa-twitter"></i>
      <i class="fa-brands fa-instagram"></i>
      <i class="fa-brands fa-youtube"></i>
      <i class="fa-brands fa-pinterest"></i>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FooterComponent'
}
</script>

<style scoped>
.footer-nav {
  padding: 3% 10%;
}

.foooter-links {
  display: flex;
  justify-content: space-around;
  align-items: center;
}

.foooter-links ul {
  display: flex;
  justify-content: space-evenly;
  list-style-type: none;
  gap: 5px;
}

.foooter-links ul li {
  font-weight: 600;
  padding: 75px;
}

.footer-horizontal-rule {
  width: 65%;
  margin: 0 auto;
  height: 2px;
  color: #000;
  margin-bottom: 56px;
}

.social-icons {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 48px;
}

.fa-brands {
  font-size: 40px;
  cursor: pointer;
}

.fa-brands:hover {
  color: #f7941e;
}
</style>