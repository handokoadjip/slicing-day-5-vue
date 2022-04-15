<template>
  <section class="py-5 my-5">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <div class="wrapper text-center">
            <h2 class="fs-3 fw-bold text-uppercase mb-3 ls-5px">crafted for creative</h2>
            <p class="mb-5 fw-bold">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ipsam error ex
              illo et!</p>
          </div>
        </div>
      </div>

      <div class="row py-2" data-masonry='{"percentPosition": true }'>
        <div class="col-6 col-lg-4 py-3">
          <div class="card border-0" style="height: 500px;">
            <figure class="m-0">
              <img src="@/assets/source/image/image-1.jpg" alt="image-1"
                style="height: 500px; width: 100%; object-fit: cover;">
            </figure>
          </div>
        </div>
        <div class="col-6 col-lg-4 py-3">
          <div class="card border-0" style="height: 250px;">
            <figure class="m-0">
              <img src="@/assets/source/image/image-2.jpg" alt="image-1"
                style="height: 250px; width: 100%; object-fit: cover;">
            </figure>
          </div>
        </div>
        <div class="col-6 col-lg-4 py-3">
          <div class="card border-0" style="height: 500px;">
            <figure class="m-0">
              <img src="@/assets/source/image/image-3.jpg" alt="image-1"
                style="height: 500px; width: 100%; object-fit: cover;">
            </figure>
          </div>
        </div>
        <div class="col-6 col-lg-4 py-3">
          <div class="card border-0" style="height: 400px;">
            <figure class="m-0">
              <img src="@/assets/source/image/image-4.jpg" alt="image-1"
                style="height: 400px; width: 100%; object-fit: cover;">
            </figure>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ContentComponent",
}
</script>