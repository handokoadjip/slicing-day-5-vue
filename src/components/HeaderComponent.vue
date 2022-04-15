<template>
  <header class="min-vh-100 bg-image-1 position-relative">
    <nav class="px-4 py-5">
      <div class="container-fluid px-0">
        <div class="row">
          <div class="col-lg-12">
            <router-link class="fs-1 navbar-brand fw-bold text-uppercase text-center d-block m-0 ls-8px" to="#">
              coastal & co
            </router-link>
          </div>
        </div>
      </div>
    </nav>
    <nav class="navbar navbar-expand-lg navbar-light px-4">
      <div class="container-fluid px-0">
        <button class="navbar-toggler mx-auto" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav text-uppercase d-flex mx-auto align-items-center">
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link" aria-current="page" to="#">newsletter</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link" to="#">view stories</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link" to="#">about</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link line py-2 px-4" to="#">suscribe</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <section>
      <div class="container">
        <div class="row">
          <div class="col-lg-12">
            <div class="wrapper text-center">
              <div class="position-absolute top-50 start-50 translate-middle mt-5">
                <h1 class="btn btn-border px-5 fs-3 fw-medium text-uppercase ls-5px">a minimalist theme</h1>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
}
</script>

