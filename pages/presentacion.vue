<template>
	
    <section>
		<div class="caption">
			<video muted autoplay loop plays-inline>
				<source src="/imagenes/video1.mp4" type="video/mp4">
			</video>
		</div>
		
		<article>
			<p class="subtle">
				Empresa dedicada a brindar personal calificado para eventos, ademas de poder realizar eventos corporativos y sociales.
				<br>Contamos con personal calificado y experimentado para que tu evento salga perfecto
			</p>
		</article>

		<aside>
			<h2 class="title">MISIÓN</h2>
			<h5 class="subtle">
				Satisfacer al 100%  a nuestros clientes, mediante la prestación  de soluciones integrales para la realización de todo tipo de eventos, que consisten en: organización, planeación, logística , decoración, renta de mobiliario, mantelería y prestación de personal de servicio.
			</h5>	
		</aside>	

		<aside>
			<h2 class="title">VISIÓN</h2>
			<h5 class="subtle">
				Ser una empresa líder y con alto prestigio en el ámbito de eventos y banquetes, tomando siempre en cuenta la innovación, perfección y las nuevas tendencias del mercado para estar siempre a la vanguardia y responder a las más altas exigencias.
			</h5>	
		</aside>
		
	</section>
	
</template>
<script>
export default {
  layout: "botones",
};
</script>

<style>

section {
  width: 100%;
  padding: 20px;
  float: left;
}
article {
  float: left;
  width: 100%;
  padding: 50px;
  position: relative;
  text-align: center;
  color: white;
  font-size: 18px;
}
h2 {
  text-align: center;
  color: #00ffab;
  font-size: 28px;
  padding: 0;
}
h5 {
  text-align: center;
  color: white;
  font-size: 18px;
  padding: 0;
}
aside {
  float: left;
  width: 50%;
  padding: 50px;
}
.caption {
  width: 100%;
  float: left;
  position: absolute;
  right: 0;
  bottom: 0;
  z-index: -1;
  opacity: 20%;
  display: flex;
  flex-content: center;
  align-content: center;
  justify-content: center;
}
video {
  width: 100%;
  flex-content: center;
  align-content: center;
}
</style>
