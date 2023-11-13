<template>

    <div> 
      <video class="custom-video" controls>
        <source :src="videoSrc" type="video/mp4">
        Tu navegador no admite la reproducción de videos.
      </video>
    </div>
  </template>
  
  <style scoped>
  .custom-video {
    width: 840px;
    height: 480px;
    border: 1px solid #ccc;
    /* otros estilos personalizados */
  }
  
  </style>

  <script>
  export default {
    data() {
      return {
        videoSrc: require('@/assets/videos/PagoReferenciado.mp4')
      };
    }
  };
  </script>

