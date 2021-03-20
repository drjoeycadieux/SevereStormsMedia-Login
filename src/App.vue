<template>
  <Home msg="Hello Vue 3 in CodeSandbox!" />
</template>

<script>
import HomeVue from "./components/Home.vue";
export default {
  name: "App",
  components: {
    Home: HomeVue,
  },
};
</script>

<style>
header {
  background-color: #2c3e50;
  color: #fff;
  margin: -14px;
  padding: 1rem 20px 100px;
  font-weight: 700;
}
h1 {
  text-align: center;
}

h1 {
  font-weight: bold;
}
</style>
