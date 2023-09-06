<template>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark padding">
  
      <b-navbar-nav class="">
        <a href="https://www.gamadero.tecnm.mx/" class="nav-link">🏠 <span class="sr-only">(current)</span></a>
        <b-nav-item-dropdown text="🏢 Nuestro campus" right> 
          <b-dropdown-item href="/NuestroCampus/Historia">Historia</b-dropdown-item>
          <b-dropdown-item href="/NuestroCampus/MisionVisionValores">Mision/Vision/Valores</b-dropdown-item>
          <b-dropdown-item href="/NuestroCampus/EstructuraOrganizacional">Estructura Organizacional</b-dropdown-item>
          <b-dropdown-item href="/NuestroCampus/Directorio">Directorio</b-dropdown-item>
          <b-dropdown-item href="/NuestroCampus/AvisoPrivacidad">Aviso de Privacidad TECNM</b-dropdown-item>
          <b-dropdown-item href="/NuestroCampus/MarcoNormativo">Marco Normativo</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="🏢 Departamentos"  right>
          <b-dropdown-item href="/Departamentos/SubdireccionAcademica">Subdirección Academica</b-dropdown-item>
          <b-dropdown-item href="/Departamentos/PRODEP">PRODEP</b-dropdown-item>
          <b-dropdown-item href="/Departamentos/SubdireccionServiciosAdministrativos">Subdirección de Servicios Administrativos</b-dropdown-item>
          <b-dropdown-item href="/Departamentos/SubdireccionPlaneacionVinculacion">Subdirección de Planeación y Vinculación</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="🏢 Oferta Educativa"  right>
          <b-dropdown-item href="/OfertaEducativa/ITICS">Ingeniería en Tecnologías de la Información y Comunicación</b-dropdown-item>
          <b-dropdown-item href="/OfertaEducativa/IGEM">Ingeniería en Gestión Empresarial</b-dropdown-item>
          <b-dropdown-item href="/OfertaEducativa/ILOG">Ingeniería en Logística</b-dropdown-item>
          <b-dropdown-item href="/OfertaEducativa/IAMB">Ingeniería Ambiental</b-dropdown-item>
          <b-dropdown-item href="/OfertaEducativa/IIND">Ingeniería Industrial</b-dropdown-item>
          <b-dropdown-item href="/OfertaEducativa/IFER">Ingeniería Ferroviaria</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="👤 Aspirantes"  right>
          <b-dropdown-item href="/Aspirantes/ConvocatoriaNuevoIngreso">Convocatoria Nuevo Ingreso</b-dropdown-item>
          <b-dropdown-item href="/Aspirantes/Cronograma">Cronograma</b-dropdown-item>
          <b-dropdown-item href="/Aspirantes/GuiaRegistro">Guia de Registro</b-dropdown-item>
          <b-dropdown-item href="http://187.188.185.18:8010/cgi-bin/sie.pl?Opc=PINDEXASPIRANTE&psie=intertec&dummy=0">SIE</b-dropdown-item>
          <b-dropdown-item href="/Aspirantes/FormatosNuevoIngreso">Formatos Nuevo Ingreso</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="🙍‍♂️ Estudiantes"  right>
          <b-dropdown-item href="http://187.188.185.18:8010/cgi-bin/sie.pl?Opc=PINDEXESTUDIANTE&psie=intertec&dummy=0">SIE</b-dropdown-item>
          <b-dropdown-item href="/Estudiantes/Reinscripcion">Reinscripción</b-dropdown-item>
          <b-dropdown-item href="/Estudiantes/ActividadesComplementarias">Actividades Complementarias</b-dropdown-item>
          <b-dropdown-item href="/Estudiantes/ServicioSocial">Servicio Social</b-dropdown-item>
          <b-dropdown-item href="/Estudiantes/ResidenciasProfesionales">Residencias Profesionales</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="👨‍🎓 Egresados"  right>
          <b-dropdown-item href="http://187.188.185.18:8010/cgi-bin/sie.pl?Opc=PINDEXESTUDIANTE&psie=intertec&dummy=0">SIE</b-dropdown-item>
          <b-dropdown-item href="/Egresados/Titulacion">Titulación</b-dropdown-item>
          <b-dropdown-item href="/Egresados/SeguimientoEgresados">Seguimiento de Egresados</b-dropdown-item>
          <b-dropdown-item href="https://docs.google.com/forms/d/e/1FAIpQLSc_Xpq5XvSq9YI1arceYkwPgN6nE21SSf_dyaUuBJMQGOXd9Q/viewform">Bolsa de Trabajo</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="👨‍🏫 Docentes"  right>
          <b-dropdown-item href="">Convocatoria</b-dropdown-item>
          <b-dropdown-item href="http://187.188.185.18:8010/cgi-bin/sie.pl?Opc=PINDEXDOCENTE&psie=intertec&dummy=0">SIE</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="👤 Vinculación" right>
          <b-dropdown-item href="/Vinculacion/Contacto">Contacto</b-dropdown-item>
          <b-dropdown-item href="#">Consejo de Vinculación</b-dropdown-item>
          <b-dropdown-item href="#">Visitas de Empresas</b-dropdown-item>
          <b-dropdown-item href="#">Widget de OCC</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="👤 C.L.E"  right>
          <b-dropdown-item href="#">Niveles</b-dropdown-item>
          <b-dropdown-item href="#">Convocatorias</b-dropdown-item>
          <b-dropdown-item href="#">Acceso</b-dropdown-item>
        </b-nav-item-dropdown>
      </b-navbar-nav>
        <b-navbar-nav class="">
        <b-nav-item-dropdown text="📚 Biblioteca"  right>
          <b-dropdown-item href="#">e-Libro Biblioteca Digital</b-dropdown-item>
          <b-dropdown-item href="#">Video e-Libro</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="💳 Pago de Servicios"  right>
          <b-dropdown-item href="#">Pago en Linea</b-dropdown-item>
          <b-dropdown-item href="#">Pago Referenciado</b-dropdown-item>
        </b-nav-item-dropdown>
      </b-navbar-nav>
    </nav>
</template>

<script>
    export default {

    }         

</script>

<style scoped>
 .navbar.navbar-dark.bg-dark{
    background-color:#013b6d!important;
  }

</style>