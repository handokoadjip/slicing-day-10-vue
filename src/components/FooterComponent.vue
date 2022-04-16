<template>
  <footer>
    <div class="container-fluid bg-black">
      <div class="row py-5">
        <div class="col-lg-12">
          <div class="wrapper d-flex flex-column flex-lg-row justify-content-between align-items-center">
            <div class="copyright d-block d-lg-flex justify-content-center align-items-center text-center">
              <div class="text-center text-fade-1 me-0 me-lg-5">
                <h2 class="mp-0 fs-3 text-uppercase fw-bold ls-7px">
                  phototastic
                </h2>
                <p class="mp-0">Lorem ipsum dolor sit amet.</p>
              </div>
              <ul class="text-uppercase d-inline mp-0">
                <li class="px-1 d-inline">
                  <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block text-fade-1" to="#">home</router-link>
                </li>
                <li class="px-1 d-inline">
                  <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block text-fade-1" to="#">shop</router-link>
                </li>
                <li class="px-1 d-inline">
                  <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block text-fade-1" to="#">gallery</router-link>
                </li>
                <li class="px-1 d-inline">
                  <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block text-fade-1" to="#">features</router-link>
                </li>
                <li class="px-1 d-inline">
                  <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block text-fade-1" to="#">blog</router-link>
                </li>
                <li class="px-1 d-inline">
                  <router-link class="nav-link fs-7 fw-bold d-lg-inline d-block text-fade-1" to="#">contact us</router-link>
                </li>
              </ul>
            </div>
            <div class="social-media">
              <div class="d-flex justify-content-center align-items-center">
                <router-link class="text-decoration-none mx-3 text-fade-1" to="#"><i class="fab fa-google-plus-g"></i></router-link>
                <router-link class="text-decoration-none mx-3 text-fade-1" to="#"><i class="fab fa-facebook-f"></i></router-link>
                <router-link class="text-decoration-none ms-3 me-5 text-fade-1" to="#"><i class="fab fa-twitter"></i></router-link>
                <router-link class="text-decoration-none mx-3 text-fade-1" to="#"><i class="fas fa-search"></i></router-link>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterComponent",
}
</script>