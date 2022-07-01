<template>
  <div class="layout-wrapper layout-content-navbar">
    <div class="layout-container">
      <!-- Menu -->
      <aside
        id="layout-menu"
        class="layout-menu-fixed menu-vertical menu bg-menu-theme"
      >
        <div class="app-brand demo">
          <router-link to="/" class="app-brand-link">
            <ZapVendasLogo></ZapVendasLogo>

            <span class="app-brand-text demo menu-text fw-bolder ms-2">
              ZapVendas
            </span>
          </router-link>

          <a
            class="layout-menu-toggle menu-link text-large ms-auto d-block d-xl-none"
          >
            <i class="bx bx-chevron-left bx-sm align-middle"></i>
          </a>
        </div>

        <div class="menu-inner-shadow"></div>

        <ul class="menu-inner py-1">
          <!-- Dashboard -->
          <li class="menu-item active">
            <router-link to="/" class="menu-link">
              <i class="menu-icon tf-icons bx bx-home-circle"></i>
              <div data-i18n="Analytics">Exemplo de Link</div>
            </router-link>
          </li>

          <li class="menu-header small text-uppercase">
            <span class="menu-header-text">Exemplo de Header</span>
          </li>
          <li class="menu-item">
            <router-link to="/" target="_blank" class="menu-link">
              <i class="menu-icon tf-icons bx bx-support"></i>
              <div data-i18n="Support">Outro Exemplo</div>
            </router-link>
          </li>
        </ul>
      </aside>
      <!-- / Menu -->

      <!-- Layout container -->
      <div class="layout-page">
        <!-- Content wrapper -->
        <div class="content-wrapper">
          <!-- Content -->

          <div class="container-xxl flex-grow-1 container-p-y">
            <div class="col-lg-12 mb-4 order-0">
              <div class="card">
                <div class="d-flex align-items-end row">
                  <div class="col-sm-7">
                    <div class="card-body">
                      <h5 class="card-title text-primary">
                        Bem-vindo ao ZapVendas
                      </h5>
                      <p class="mb-4">
                        Você configurou com sucesso o layout inicial do projeto!
                      </p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <!-- / Content -->

          <!-- Footer -->
          <footer class="content-footer footer bg-footer-theme">
            <div
              class="container-xxl d-flex flex-wrap justify-content-between py-2 flex-md-row flex-column"
            >
              <div class="mb-2 mb-md-0">
                Curso de Vue.Js © 2022. Tema gratuito em
                <a
                  href="https://themeselection.com"
                  target="_blank"
                  class="footer-link fw-bolder"
                  >ThemeSelection</a
                >
              </div>
              <div>
                <a
                  href="https://google.com/"
                  target="_blank"
                  class="footer-link me-4"
                >
                  Link 1
                </a>
                <a
                  href="https://google.com/"
                  target="_blank"
                  class="footer-link me-4"
                >
                  Link 2
                </a>
                <a
                  href="https://google.com/"
                  target="_blank"
                  class="footer-link me-4"
                >
                  Link 3
                </a>
              </div>
            </div>
          </footer>
          <!-- / Footer -->

          <div class="content-backdrop fade"></div>
        </div>
        <!-- Content wrapper -->
      </div>
      <!-- / Layout page -->
    </div>
  </div>
</template>

<script setup>
import ZapVendasLogo from "./components/ZapVendasLogo.vue";
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Public+Sans:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&display=swap");
@import "./assets/core.css";
@import "./assets/theme-default.css";
@import "./assets/fonts/boxicons.css";
</style>
