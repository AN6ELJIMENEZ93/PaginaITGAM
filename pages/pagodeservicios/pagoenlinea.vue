<template>
    <div>
    <b><strong><h2  align="center" style="color:#272727; font-family:'Lucida Fax'; font-size:25px"> FORMA DE PAGO EN LINEA</h2></strong></b> 
      <center><VideoPlayer /></center> <br>
      <center><a class="custom-button" href="https://www.gamadero.tecnm.mx/banamex/index.php">Realizar pago</a></center>

    </div>
  </template>
  
  <script>
  import VideoPlayer from '~/components/VideoPlayer.vue';
  
  export default {
    components: {
      VideoPlayer
    }
  };
  </script>

<style scoped>
.custom-button {
  background-color: #31a1d4; /* Color de fondo del botón */
  color: rgb(0, 0, 0); /* Color del texto del botón */
  padding: 10px 20px; /* Espaciado interno del botón */
  border: 2px solid #161515; /* Borde del botón */
  border-radius: 10px;
  cursor: pointer; /* Estilo del cursor al pasar por encima */
  font-size: 16px; /* Tamaño de la fuente */
  font-family: "Lucida Fax"; /* Cambiar el estilo de letra del botón */
  font-weight: bold; /* Hacer que el texto sea negrita */
  transition: background-color 0.3s ease-in-out; /* Transición para el cambio de color de fondo */
  
}

.custom-button:hover {
  background-color: #1e6586; /* Nuevo color de fondo al pasar por encima */
}
</style>