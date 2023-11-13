<template>
  <div>
    <div> <br><br><br>
      <Carrusel />
    </div>
    <Cuerpo />
    <FooterComunicacion />
  </div>
</template>

<script>
import { largeCardSections, smallCardSections } from "@/assets/data.js";
import Default from "../layouts/default.vue";
export default {
   
    components: { Default }
}
</script>
