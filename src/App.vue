<template>
  <v-container>
    <v-layout>
      <product />
    </v-layout>
  </v-container>
</template>

<script>
import product from "@/components/Product.vue";
export default {
  name: "App",
  components: {
    product,
  },
};
</script>

<style>
body {
  background: #f3eae3;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
