<template>
  <div id="home">
    <div class="data-personal">
      <div>Name: {{ name }}</div>
      <div>Age: {{ age }}</div>
      <div>Address: {{ address }}</div>
      <div>Phone: {{ phone }}</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderSection",
  props: {
    name: String,
    age: Number,
    address: String,
    phone: String,
  },
};
</script>

<style scoped>
#home {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100vh;
  color: #333;
}

.data-personal {
  font-weight: bold;
  text-align: left;
}
</style>
