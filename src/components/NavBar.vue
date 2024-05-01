<template>
  <div id="navbar">
    <div><img src="./../assets/logo.png" class="logo" /></div>
    <div class="nav">
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#service">Service</a>
      <a href="#contact">Contact</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "NavBar",
};
</script>

<style scoped>
#navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #333;
  color: white;
  padding: 10px 200px;
}

.logo {
  width: 50px;
  height: 50px;
}

.nav {
  display: flex;
  color: white;
  font-weight: bold;
  justify-content: space-between;
  width: 75%;
}

.nav a {
  transition: all 300ms ease-in-out 150ms;
  color: white;
  text-decoration: none;
}

.nav a:hover {
  cursor: pointer;
  color: #f1c40f;
}
</style>
