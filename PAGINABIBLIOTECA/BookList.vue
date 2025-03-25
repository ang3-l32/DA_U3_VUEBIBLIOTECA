<template>
    <div class="container mt-4">
      <h2>Libros Disponibles</h2>
      <div class="row">
        <div class="col-md-4" v-for="book in books" :key="book.id">
          <div class="card">
            <img :src="book.image" class="card-img-top" alt="book.title">
            <div class="card-body">
              <h5 class="card-title">{{ book.title }}</h5>
              <p class="card-text">{{ book.author }}</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script setup>
  import { ref } from 'vue';
  const books = ref([
    { id: 1, title: "El principito", author: "Antoine de Saint-Exupéry", image: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTMab9s-8airRwyzGQuyQoaX0wcTtobkNfb7w&s" },
    { id: 2, title: "Cien años de soledad", author: "Gabriel García Márquez", image: "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTwSsR0pOIFUZYQivZGvfV1a74s4Khz8GrbjA&s" },  
    { id: 3, title: "1984", author: "George Orwell", image: "" }
])
  </script>
  
  <style scoped>
  .card {
    margin: 15px;
    border-radius: 10px;
  }
  </style>
  