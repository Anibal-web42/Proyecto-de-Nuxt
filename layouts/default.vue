<template>
    <div>
      <nav>
        <ul>
          <li><nuxt-link to="/">Inicio</nuxt-link></li>
          <li><nuxt-link to="/about">Sobre Nosotros</nuxt-link></li>
          <li><nuxt-link to="/contact">Contacto</nuxt-link></li>
        </ul>
      </nav>
      <main>
        <NuxtPage />
      </main>
    </div>
  </template>
  
  <script setup>
  </script>
  
  <style scoped>
  nav {
    background-color: #007bff;
    padding: 10px;
  }
  
  ul {
    list-style: none;
    display: flex;
    justify-content: space-around;
    margin: 0;
    padding: 0;
  }
  
  li {
    margin: 0;
  }
  
  a {
    color: white;
    text-decoration: none;
    font-size: 16px;
  }
  
  a:hover {
    text-decoration: underline;
  }
  
  main {
    padding: 20px;
  }
  </style>