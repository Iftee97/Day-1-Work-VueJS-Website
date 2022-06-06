<template>
  <nav class="nav">
    <a href="#" class="logo-link">
      <img src="../assets/logo.png" alt="logo-1" class="logo" />
    </a>

    <ul class="nav-ul">
      <li class="nav-li">
        <a href="#" class="nav-link">Home</a>
      </li>

      <li class="nav-li">
        <a href="#" class="nav-link">About</a>
      </li>

      <li class="nav-li">
        <a href="#" class="nav-link">Services</a>
      </li>

      <li class="nav-li">
        <a href="#" class="nav-link">Blogs</a>
      </li>
    </ul>

    <button class="nav-btn">GIFT FINDER</button>
  </nav>
</template>

<script>
export default {
  name: "NavbarMenu",
};
</script>

<style scoped>
.nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 35px;
  font-family: "Khula", sans-serif;
}

.logo {
  font-size: 18px;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 30px;
}

.nav-link {
  text-decoration: none;
  color: #000;
}

.nav-link:hover {
  color: #f7941e;
}

.nav-btn {
  color: #f7941e;
  border: 1px solid #f7941e;
  border-radius: 5px;
  padding: 8px 16px;
  background: #fafafa;
}

.nav-btn:hover {
  color: #000;
  background-color: #f7941e;
}
</style>