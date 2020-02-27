<template>
  <div class="wrapper">
        <!-- Sidebar  -->
        <nav id="sidebar">
            <div class="sidebar-header">
                <!-- <img src="../assets/image.svg" class="mx-auto d-block" width="200" height="145"> -->
                <img src="http://placehold.it/200x145?text=Logo" class="mx-auto d-block">
            </div>

            <ul class="list-unstyled components">
                <li>
                    <a href="#"><i class="fas fa-th-large mr-3"></i>Dashboard</a>
                </li>
                <li>
                    <a href="#"><i class="fa fa-lg fa-user mr-3"></i>Perfil</a>
                </li>
                <li>
                    <a href="#"><i class="fas fa-list mr-3"></i>Categorias</a>
                </li>
                <li>
                    <a href="#"><i class="fas fa-poll mr-3"></i>Estatísticas</a>
                </li>
                <li>
                    <a href="#"><i class="far fa-question-circle mr-3"></i>Suporte</a>
                </li>
            </ul>
        </nav>

        <!-- Page Content  -->
        <div id="content">

            <!-- navbar -->
            <nav class="navbar navbar-expand-lg navbar-light bg-light">
                <button type="button" id="sidebarCollapse" class="btn btn-outline-primary">
                    <i class="fas fa-bars"></i>
                </button>

                <div class="navbar-nav ml-auto">
                    <a class="nav-link mr-2" href="#"><i class="fa fa-bell fa-lg" hidden></i></a>
                </div>

                <div class="dropdrown">
                    <a class="nav-link dropdown-toggle" data-toggle="dropdown" href="#">
                        <i class="fa fa-lg fa-user-circle mr-1"></i>User
                    </a>
                    <div class="dropdown-menu dropdown-menu-right">
                        <a class="dropdown-item" href="#">Perfil</a>
                        <a class="dropdown-item" href="#">Ajuda</a>
                        <div class="dropdown-divider"></div>
                        <a class="dropdown-item" href="#">Sair</a>
                    </div>

                </div>
            </nav>

            <!-- Data -->
            <div id="data">

                <div class="row">
                </div>

            </div>

        </div>
    </div>
</template>

<script>

import $ from 'jquery'

export default {

  mounted() {

    $(document).ready(function () {
            $('#sidebarCollapse').on('click', function () {
                $('#sidebar').toggleClass('active')
            })
        })

  }

}
</script>

<style>

</style>