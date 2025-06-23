<template>
  <header class="header">
    <nav>
      <router-link to="/">Главная</router-link> |
      <router-link to="/about">О сайте</router-link> |
      <router-link to="/products">Продукты</router-link> |
      <router-link to="/contact">Контакты</router-link>
    </nav>
  </header>
</template>

<style scoped>
.header {
  background-color: #333;
  padding: 1rem;
  color: white;
  text-align: center;
}
nav a {
  color: white;
  margin: 0 10px;
  text-decoration: none;
}
</style>
