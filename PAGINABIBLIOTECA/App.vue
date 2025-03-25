<template>
  <div id="app">
    <Navbar />
    <Banner />
    <BookList />
  </div>
</template>

<script setup>
import Navbar from "./Navbar.vue";
import Banner from "./Banner.vue";
import BookList from "./BookList.vue";

</script>

<style scoped>
#app {
  font-family: Arial, sans-serif;
  background-color: #e0f2ff;
  color: #003366;
  min-height: 100vh;
  text-align: center;
}
</style>
