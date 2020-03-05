<template>
  <div class="wrapper">
    <!-- Sidebar  -->
    <nav id="sidebar">
      <div class="sidebar-header">
        <!-- <img src="../assets/image.svg" class="mx-auto d-block" width="200" height="145"> -->
        <img src="http://placehold.it/200x145?text=Logo" class="mx-auto d-block" />
      </div>

      <ul class="list-unstyled components">
        <li>
          <a href="#">
            <svg
              class="bi bi-columns-gutters mr-1"
              width="30"
              height="30"
              viewBox="0 0 20 20"
              fill="currentColor"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                d="M8 3H3v3h5V3zM3 2a1 1 0 00-1 1v3a1 1 0 001 1h5a1 1 0 001-1V3a1 1 0 00-1-1H3zm14 12h-5v3h5v-3zm-5-1a1 1 0 00-1 1v3a1 1 0 001 1h5a1 1 0 001-1v-3a1 1 0 00-1-1h-5zm-4-3H3v7h5v-7zM3 9a1 1 0 00-1 1v7a1 1 0 001 1h5a1 1 0 001-1v-7a1 1 0 00-1-1H3zm14-6h-5v7h5V3zm-5-1a1 1 0 00-1 1v7a1 1 0 001 1h5a1 1 0 001-1V3a1 1 0 00-1-1h-5z"
                clip-rule="evenodd"
              />
            </svg>Dashboard
          </a>
        </li>
        <li>
          <a href="#">
            <svg
              class="bi bi-person"
              width="30"
              height="30"
              viewBox="0 0 20 20"
              fill="currentColor"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                d="M15 16s1 0 1-1-1-4-6-4-6 3-6 4 1 1 1 1h10zm-9.995-.944v-.002zM5.022 15h9.956a.274.274 0 00.014-.002l.008-.002c-.001-.246-.154-.986-.832-1.664C13.516 12.68 12.289 12 10 12c-2.29 0-3.516.68-4.168 1.332-.678.678-.83 1.418-.832 1.664a1.05 1.05 0 00.022.004zm9.974.056v-.002zM10 9a2 2 0 100-4 2 2 0 000 4zm3-2a3 3 0 11-6 0 3 3 0 016 0z"
                clip-rule="evenodd"
              />
            </svg>
            Perfil
          </a>
        </li>
        <li>
          <a href="#">
            <svg
              class="bi bi-list-ul mr-1"
              width="30"
              height="30"
              viewBox="0 0 20 20"
              fill="currentColor"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                d="M7 13.5a.5.5 0 01.5-.5h9a.5.5 0 010 1h-9a.5.5 0 01-.5-.5zm0-4a.5.5 0 01.5-.5h9a.5.5 0 010 1h-9a.5.5 0 01-.5-.5zm0-4a.5.5 0 01.5-.5h9a.5.5 0 010 1h-9a.5.5 0 01-.5-.5zm-3 1a1 1 0 100-2 1 1 0 000 2zm0 4a1 1 0 100-2 1 1 0 000 2zm0 4a1 1 0 100-2 1 1 0 000 2z"
                clip-rule="evenodd"
              />
            </svg>Categorias
          </a>
        </li>
        <li>
          <a href="#">
            <svg
              class="bi bi-graph-up mr-1"
              width="30"
              height="30"
              viewBox="0 0 20 20"
              fill="currentColor"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path d="M2 2h1v16H2V2zm1 15h15v1H3v-1z" />
              <path
                fill-rule="evenodd"
                d="M16.39 6.312l-4.349 5.437L9 8.707l-3.646 3.647-.708-.708L9 7.293l2.959 2.958 3.65-4.563.781.624z"
                clip-rule="evenodd"
              />
              <path
                fill-rule="evenodd"
                d="M12 5.5a.5.5 0 01.5-.5h4a.5.5 0 01.5.5v4a.5.5 0 01-1 0V6h-3.5a.5.5 0 01-.5-.5z"
                clip-rule="evenodd"
              />
            </svg>Estatísticas
          </a>
        </li>
        <li>
          <a href="#">
            <svg
              class="bi bi-question mr-1"
              width="30"
              height="30"
              viewBox="0 0 20 20"
              fill="currentColor"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                d="M10 17a7 7 0 100-14 7 7 0 000 14zm8-7a8 8 0 11-16 0 8 8 0 0116 0z"
                clip-rule="evenodd"
              />
              <path
                d="M7.25 8.033h1.32c0-.781.458-1.384 1.36-1.384.685 0 1.313.343 1.313 1.168 0 .635-.374.927-.965 1.371-.673.489-1.206 1.06-1.168 1.987l.007.463h1.307v-.355c0-.718.273-.927 1.01-1.486.609-.463 1.244-.977 1.244-2.056 0-1.511-1.276-2.241-2.673-2.241-1.326 0-2.786.647-2.754 2.533zm1.562 5.516c0 .533.425.927 1.01.927.609 0 1.028-.394 1.028-.927 0-.552-.42-.94-1.029-.94-.584 0-1.009.388-1.009.94z"
              />
            </svg>Suporte
          </a>
        </li>
      </ul>
    </nav>

    <!-- Page Content  -->
    <div id="content">
      <!-- navbar -->
      <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <button type="button" id="sidebarCollapse" class="btn btn-outline-primary btn-sm">
          <svg
            class="bi bi-list"
            width="24"
            height="24"
            viewBox="0 0 20 20"
            fill="currentColor"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              fill-rule="evenodd"
              d="M4.5 13.5A.5.5 0 015 13h10a.5.5 0 010 1H5a.5.5 0 01-.5-.5zm0-4A.5.5 0 015 9h10a.5.5 0 010 1H5a.5.5 0 01-.5-.5zm0-4A.5.5 0 015 5h10a.5.5 0 010 1H5a.5.5 0 01-.5-.5z"
              clip-rule="evenodd"
            />
          </svg>
        </button>

        <div class="navbar-nav ml-auto">
          <a class="nav-link mr-2" href="#" hidden>
            <svg
              class="bi bi-bell-fill"
              width="30"
              height="30"
              viewBox="0 0 20 20"
              fill="currentColor"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                d="M10 18a2 2 0 002-2H8a2 2 0 002 2zm.995-14.901a1 1 0 10-1.99 0A5.002 5.002 0 005 8c0 1.098-.5 6-2 7h14c-1.5-1-2-5.902-2-7 0-2.42-1.72-4.44-4.005-4.901z"
              />
            </svg>
            <span class="badge badge-pill badge-danger">1</span>
          </a>
        </div>

        <div class="dropdrown">
          <a class="nav-link dropdown-toggle" data-toggle="dropdown" href="#">
            <span class="dot-user mr-1">
              <svg
                class="bi bi-person"
                width="30"
                height="30"
                viewBox="0 0 22 21"
                fill="currentColor"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M15 16s1 0 1-1-1-4-6-4-6 3-6 4 1 1 1 1h10zm-9.995-.944v-.002zM5.022 15h9.956a.274.274 0 00.014-.002l.008-.002c-.001-.246-.154-.986-.832-1.664C13.516 12.68 12.289 12 10 12c-2.29 0-3.516.68-4.168 1.332-.678.678-.83 1.418-.832 1.664a1.05 1.05 0 00.022.004zm9.974.056v-.002zM10 9a2 2 0 100-4 2 2 0 000 4zm3-2a3 3 0 11-6 0 3 3 0 016 0z"
                  clip-rule="evenodd"
                />
              </svg>
            </span>User
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
        <div class="row"></div>
      </div>
    </div>
  </div>
</template>

<script>
import $ from "jquery";
export default {
  mounted() {
    $(document).ready(function() {
      $("#sidebarCollapse").on("click", function() {
        $("#sidebar").toggleClass("active");
      });
    });
  }
};
</script>

<style>
</style>