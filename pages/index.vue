<template >
  <div class="row d-flex justify-content-center">
    <img src="/imagenes/banner.png" class="mt-4 mb-5" style="border-radius: 50px; width: 90%; height: 300px;" />
    <div class="col-md-12">
      <div
        id="carouselExampleIndicators"
        class="carousel slide"
        data-bs-ride="carousel"
      >
        <div class="carousel-indicators">
          <button
            type="button"
            data-bs-target="#carouselExampleIndicators"
            data-bs-slide-to="0"
            class="active"
            aria-current="true"
            aria-label="Slide 1"
          ></button>
          <button
            type="button"
            data-bs-target="#carouselExampleIndicators"
            data-bs-slide-to="1"
            aria-label="Slide 2"
          ></button>
          <button
            type="button"
            data-bs-target="#carouselExampleIndicators"
            data-bs-slide-to="2"
            aria-label="Slide 3"
          ></button>
        </div>
        <div class="carousel-inner ">
          <div class="row d-flex justify-content-center">
             <div class="col-sm-10 col-xs-11 col-md-8" style="padding: 5px 0;">
                <div class="carousel-item active">
              <img src="/imagenes/img1.png" class="d-block" />
            </div>
            <div class="carousel-item">
              <img src="/imagenes/img2.png" class="d-block" />
            </div>
            <div class="carousel-item">
              <img src="/imagenes/img3.png" class="d-block" />
            </div>
             </div>
          </div>
        </div>
        <button
          class="carousel-control-prev"
          type="button"
          data-bs-target="#carouselExampleIndicators"
          data-bs-slide="prev"
        >
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button
          class="carousel-control-next"
          type="button"
          data-bs-target="#carouselExampleIndicators"
          data-bs-slide="next"
        >
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  mounted() {
    const carousel = new this.$b.Carousel("#carouselExampleIndicators");
  },
  name: "IndexPage",
};
</script>
<style scoped>
img {
  height:auto;
  width: 100%;
}
.imgfondo {
  background-image: url("/imagenes/lovepik.png");
  background-position: center;
  background-size: contain;
  height: 150px;
}
</style>