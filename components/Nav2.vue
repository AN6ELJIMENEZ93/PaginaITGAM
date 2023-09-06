<template>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark padding">
        <a class="navbar-brand"> <img src="@/assets/images/banner.png" width="800" height="100"> </a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse ml-auto" id="navbarSupportedContent">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a href="https://www.gob.mx/tramites" class="nav-link"> <img src="@/assets/images/correo-icono.png"> <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item active">
                    <a href="@/assets/documents/Calendario Escolar Agosto-diciembre 2023.pdf" class="nav-link"> <img src="@/assets/images/calendario-icono.png"> <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item active">
                    <a class="btn btn-outline-info" href="https://docs.google.com/forms/d/e/1FAIpQLSf9O2d-IwxCyBMMigDTcGS6r-27LMCj1I9VOfImrq2pnr5aJg/viewform" target="_blank">Consulta Aqui</a>
                </li>
            </ul>
        </div>
    </nav>
</template>

<script>
    export default {

    }         

</script>

<style scoped>
 .navbar.navbar-dark.bg-dark{
    background-color: rgb(255, 255, 255)!important;
 }
    .nav-left {
        margin-left: auto;
    }
</style>