<template>
  <div>
    <Header />
    <h1>Home Pages</h1>
  </div>
</template>

<script>
import Header from "../components/Header";

export default {
  name: "Home",
  components: {
    Header,
  },
};
</script>
<style scoped>
p {
  text-align: center;
  color: firebrick;
  font-weight: bold;
}
</style>