<template >
  <section>
		<div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel" >
		<div class="carousel-indicators">
			<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
			<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
			<button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
		</div>
		<div class="carousel-inner">
			<div class="carousel-item active">
				<img src="/imagenes/img1.png" class="d-block w-100" >
			</div>
			<div class="carousel-item">
				<img src="/imagenes/img2.png" class="d-block w-100">
			</div>
			<div class="carousel-item">
				<img src="/imagenes/img3.png" class="d-block w-100" >
			</div>
		</div>
		<button class="carousel-control-prev button" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
			<span class="carousel-control-prev-icon" aria-hidden="true"></span>
			<span class="visually-hidden">Previous</span>
		</button>
		<button class="carousel-control-next button" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
			<span class="carousel-control-next-icon" aria-hidden="true"></span>
			<span class="visually-hidden">Next</span>
		</button>
		</div>

	<div class="buttonsmain">
		<button type="button" class="btn btn-outline-info"><a href="#">Vitrina de Talentos</a></button>
		<button type="button" class="btn btn-outline-info"><a href="#">Registra tus datos</a></button>
	</div>
	</section>
	
</template>

<script>

export default {
  mounted(){
     const carousel = new this.$b.Carousel('#carouselExampleIndicators')
  },
  name: 'IndexPage'
}
</script>

<style>
	section{
		background-color: black;
	}
	.buttonsmain{
		gap: 15px;
	}
</style>
