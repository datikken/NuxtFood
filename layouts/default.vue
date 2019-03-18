<template>
<div class="app">
<div class="navbar">
  <div class="nav_left">
    <ul>
      <li>Рестораны</li>
      <li>Доставка</li>
      <li>Караоке</li>
    </ul>
  </div>
  <h1 class="logo">Navbar</h1>
  <div class="nav_right">
    <ul>
      <li>О нас</li>
      <li>Новости</li>
      <li>Контакты</li>
    </ul>
  </div>
</div>  
  <nuxt />  
  </div>
</template>

<style>
.navbar {
  display: flex;
  justify-content: center;
}

.nav_left ul {
  display: flex;
  list-style: none;
}

.nav_left ul li {
  margin: 20px;
}

.logo {
  background-color: red;
}

.nav_right ul {
  display: flex;
  list-style: none;
}

.nav_right ul li {
  margin: 20px;
}

</style>