<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark padding">
      <b-navbar-nav class="">
        <NuxtLink to="#" class="nav-link">🏠 <span class="sr-only">(current)</span></NuxtLink>
        <b-nav-item-dropdown text="🏢 Nuestro campus" right> 
          <b-dropdown-item><NuxtLink to="/NuestroCampus/Historia">Historia</NuxtLink></b-dropdown-item>
          <b-dropdown-item><NuxtLink to="/NuestroCampus/MisionVisionValores">MisionVisionValores</NuxtLink></b-dropdown-item>
          <b-dropdown-item><NuxtLink to="/NuestroCampus/EstructuraOrganizacional">Estructura Organizacional</NuxtLink></b-dropdown-item>
          <b-dropdown-item><NuxtLink to="/NuestroCampus/Directorio">Directorio</NuxtLink></b-dropdown-item>
          <b-dropdown-item href="../../documents/NuestroCampus/Proyecto_Aviso_Privacidad_TecNM.pdf" target="blank">Aviso de Privacidad TECNM</b-dropdown-item>
          <b-dropdown-item><NuxtLink to="/NuestroCampus/MarcoNormativo">Marco Normativo</NuxtLink></b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="🏢 Oferta Educativa"  right>
          <b-dropdown-item><NuxtLink to="/OfertaEducativa/ITICS">Ingeniería en Tecnologías de la Información y Comunicación</NuxtLink></b-dropdown-item>
          <b-dropdown-item><NuxtLink to="/OfertaEducativa/IGEM">Ingeniería en Gestión Empresarial</NuxtLink></b-dropdown-item>
          <b-dropdown-item><NuxtLink to="/OfertaEducativa/ILOG">Ingeniería en Logistica</NuxtLink></b-dropdown-item>
          <b-dropdown-item><NuxtLink to="/OfertaEducativa/IAMB">Ingeniería Ambiental</NuxtLink></b-dropdown-item>
          <b-dropdown-item><NuxtLink to="/OfertaEducativa/IIND">Ingeniería Industial</NuxtLink></b-dropdown-item>
          <b-dropdown-item><NuxtLink to="/OfertaEducativa/IFER">Ingeniería Ferroviaria</NuxtLink></b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="👤 Aspirantes"  right>
          <b-dropdown-item href="../../documents/aspirantes/convocatoria_ene_jun_2024.pdf"  target="blank">Convocatoria Nuevo Ingreso</b-dropdown-item>
          <b-dropdown-item href="../../documents/aspirantes/cronograma_ene_jun_2023_1_2.pdf" target="blank">Cronograma</b-dropdown-item>
          <b-dropdown-item href="../../documents/aspirantes/guia_de_registro_ene_jun_2024_1.pdf" target="blank">Guia de Registro</b-dropdown-item>
          <b-dropdown-item href="http://187.188.185.18:8010/cgi-bin/sie.pl?Opc=PINDEXASPIRANTE&psie=intertec&dummy=0" target="blank">SIE</b-dropdown-item>
          <b-dropdown-item><NuxtLink to="/Aspirantes/FormatosNuevoIngreso">Formatos Nuevo Ingreso</NuxtLink></b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="🙍‍♂️ Estudiantes"  right>
          <b-dropdown-item href="http://187.188.185.18:8010/cgi-bin/sie.pl?Opc=PINDEXESTUDIANTE&psie=intertec&dummy=0" target="blank">SIE</b-dropdown-item>
          <b-dropdown-item href="/Estudiantes/Reinscripcion">Reinscripción</b-dropdown-item>
          <b-dropdown-item href="../../documents/estudiantes/catalogo_programa_de_actividades_complementarias.pdf">Actividades Complementarias</b-dropdown-item>
          <b-dropdown-item href="/Estudiantes/ServicioSocial">Servicio Social</b-dropdown-item>
          <b-dropdown-item href="/Estudiantes/ResidenciasProfesionales">Residencias Profesionales</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="👨‍🎓 Egresados"  right>
          <b-dropdown-item href="http://187.188.185.18:8010/cgi-bin/sie.pl?Opc=PINDEXESTUDIANTE&psie=intertec&dummy=0" target="blank">SIE</b-dropdown-item>
          <b-dropdown-item href="/Egresados/Titulacion">Titulación</b-dropdown-item>
          <b-dropdown-item href="/Egresados/SeguimientoEgresados">Seguimiento de Egresados</b-dropdown-item>
          <b-dropdown-item href="https://docs.google.com/forms/d/e/1FAIpQLSc_Xpq5XvSq9YI1arceYkwPgN6nE21SSf_dyaUuBJMQGOXd9Q/viewform">Bolsa de Trabajo</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="👨‍🏫 Docentes"  right>
          <b-dropdown-item href="/Docentes/Convocatorias">Convocatoria</b-dropdown-item>
          <b-dropdown-item href="http://187.188.185.18:8010/cgi-bin/sie.pl?Opc=PINDEXDOCENTE&psie=intertec&dummy=0">SIE</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="👤 Vinculación" right>
          <b-dropdown-item href="/Vinculacion/Contacto">Contacto</b-dropdown-item>
          <b-dropdown-item href="../../documents/vinculacion/hoja_consejo_de_vinculacion_para_publicar.pdf" target="blank">Consejo de Vinculación</b-dropdown-item>
          <b-dropdown-item href="../../documents/vinculacion/anexo_tres_vin.pdf" target="blank">Visitas de Empresas</b-dropdown-item>
          <b-dropdown-item href="../../documents/vinculacion/tutorial_occmundial_widget_de_empleo.pdf" target="blank">Widget de OCC</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="👤 C.L.E"  right>
          <b-dropdown-item a href="../../documents/cle/anexo_cuatro_ingles.pdf" target="blank">Niveles</b-dropdown-item>
          <b-dropdown-item href="/CLE/Convocatorias">Convocatorias</b-dropdown-item>
          <b-dropdown-item href="#">Acceso</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="📚 Biblioteca"  right>
          <b-dropdown-item href="https://elibro.net/es/lc/gamadero/login_usuario/?next=/es/lc/gamadero/inicio/" target="blank">e-Libro Biblioteca Digital</b-dropdown-item>
          <b-dropdown-item href="/Biblioteca/VideoE-libro">Video e-Libro</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="💳 Pago de Servicios"  right>
          <b-dropdown-item href="/pagodeservicios/pagoenlinea">Pago en Linea</b-dropdown-item>
          <b-dropdown-item href="/pagodeservicios/pagoreferenciado">Pago Referenciado</b-dropdown-item>
          

        </b-nav-item-dropdown>
      </b-navbar-nav>
    </nav> <br><br>
  </div> 
</template>

<script>
    export default {

    }         

</script>

<style scoped>
 .navbar.navbar-dark.bg-dark{
    background-color:#013b6d!important;
    top: 230px;
    position: fixed;
    width: 100%;
    z-index: 9999;
  }

</style>