<template>
  <nav class="nav">
    <img src="../assets/logo.png" alt="logo-1" class="logo" />

    <ul class="nav-ul">
      <li class="nav-li">Home</li>
      <li class="nav-li">About</li>
      <li class="nav-li">Services</li>
      <li class="nav-li">Blogs</li>
    </ul>

    <button class="nav-btn">GIFT FINDER</button>
  </nav>
</template>

<script>
export default {
  name: 'NavbarMenu'
}
</script>

<style scoped>
.nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 35px;
  font-family: 'Khula', sans-serif;
}

.logo {
  font-size: 18px;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 30px;
}

.nav-btn {
  color: #F7941E;
  border: 1px solid #F7941E;
  border-radius: 5px;
  padding: 8px 16px;
  background: #FAFAFA;
}
</style>