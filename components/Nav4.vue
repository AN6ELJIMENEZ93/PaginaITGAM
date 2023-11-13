<template>
   <nav class="menu">
  <ul>
    <li><a href="#">Inicio</a></li>
    <li><a href="#">Acerca de</a></li>
    <li><a href="#">Servicios</a></li>
    <li><a href="#">Contacto</a></li>
  </ul>
</nav>
</template>

<style scoped>
.menu {
  display: none;
}

.menu ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

.menu li {
  display: inline-block;
  margin-right: 20px;
}

.menu a {
  text-decoration: none;
  color: #000;
}
</style>