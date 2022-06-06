<template>
  <div class="container-fluid footer-nav">
    <div class="foooter-links">
      <ul class="footer-ul">
        <li class="footer-link">
          <a href="#">Home</a>
        </li>

        <li class="footer-link">
          <a href="#">About</a>
        </li>
      </ul>

      <img src="../assets/logo2.png" alt="logo-2" class="logo" />

      <ul>
        <li class="footer-link">
          <a href="#">Service</a>
        </li>

        <li class="footer-link">
          <a href="#">Blog</a>
        </li>
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
  name: "FooterComponent",
};
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

.footer-link a {
  text-decoration: none;
  color: #000;
}

.footer-link a:hover {
  color: #f7941e;
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