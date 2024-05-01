<template>
  <NavBar />
  <HeaderSection name="Fery Anuar" age="22" address="Bogor" phone="083813479771" />
</template>

<script>
import NavBar from "./components/NavBar.vue";
import HeaderSection from "./components/HeaderSection.vue";

export default {
  name: "App",
  components: {
    NavBar,
    HeaderSection,
  },
};
</script>

<style>
body {
  padding: 0;
  margin: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
