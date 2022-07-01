<template>
    <main presentation>
		<h2>NUESTROS SERVICIOS</h2>
		<div class="caption">
			<video muted autoplay loop plays-inline>
				<source src="/imagenes/video1.mp4" type="video/mp4">
			</video>
		</div>
		<section>
				<div class="card" style="width: 18rem;">
					<img src="/imagenes/1.png" class="card-img-top" alt="...">
					<div class="card-body">
						<h5 class="card-title">EVENTOS Y REUNIONES EMPRESA - OPC</h5>
						<p class="card-text">Congresos, conferencias, convenciones, ferias, exposiciones, workshops, cofe breaks, reuniones de trabajo, sesiones de networking</p>
					</div>
				</div>
				<div class="card" style="width: 18rem;">
					<img src="/imagenes/2.png" class="card-img-top" alt="...">
					<div class="card-body">
						<h5 class="card-title">COMUNICACIÓN CORPORATIVA Y NUEVAS TECNOLOGÍAS</h5>
						<p class="card-text">Presentaciones, lanzamientos de productos y marcas, roadshows, street marketing, btl, entretenimiento audiovisual con Videomapping, comunicación digital en eventos</p>
					</div>
				</div>
				<div class="card" style="width: 18rem;">
					<img src="/imagenes/3.png" class="card-img-top" alt="...">
					<div class="card-body">
						<h5 class="card-title">EVENTOS CORPORATIVOS PRIVADOS</h5>
						<p class="card-text">Fiestas y aniversarios de empresas, Fiestas privadas, Celebraciones, comidas y cenas de empresa, ceremonia de entrega de premios, inauguraciones de locales y sedes, family days</p>
					</div>
				</div>
				<div class="card" style="width: 18rem;">
					<img src="/imagenes/4.png" class="card-img-top" alt="...">
					<div class="card-body">
						<h5 class="card-title">EVENTOS DEPORTIVOS CORPORATIVOS Y PRIVADOS</h5>
						<p class="card-text">Organización de eventos y torneos deportivos y organización de carreras populares</p>
					</div>
				</div>
				<div class="card" style="width: 18rem;">
					<img src="/imagenes/5.png" class="card-img-top" alt="...">
					<div class="card-body">
						<h5 class="card-title">PERSONAL CALIFICADO</h5>
						<p class="card-text">Disponemos de los profesionales más cualificados, de los mejores y más avanzados medios técnicos</p>
					</div>
				</div>
		</section>			
	</main>
</template>
<style>
	main{
		width: 100%;
	}
	section{
		display: flex;
		flex-wrap: wrap;
		width: 100%;
		justify-content: center;
		align-content: center;
	}
	.card{
		background: black;
		border: solid #00ffab 1px;
		margin: 10px;
	}
	h2{
        text-align: center;
        color: #00ffab;
        font-size: 28px;
    }
	h5{
        text-align: left;
        color: #00ffab;
        font-size: 18px;
		text-align: center;
    }
	p{
		color: white;
		text-align: center;
	}
	.caption{
		width:100%;
		float: left;
		position: absolute;
		right: 0;
		bottom: 0;
		z-index: -1;
		opacity: 50%;
		display: flex;
		flex-content: center;
		align-content: center;
		justify-content: center;
		
	}
	video{
		width:100%;
		flex-content: center;
		align-content: center;
	}
</style>
