<template>
    <main presentation>
		<section>
			
			<div class="caption">
				<video muted autoplay loop plays-inline>
					<source src="/imagenes/video1.mp4" type="video/mp4">
				</video>
			</div>
			
			<article>
				<h2>TE OFRECEMOS</h2>
					<h5>EVENTOS Y REUNIONES EMPRESA - OPC</h5>
					<p class="subtle">
						Empresa dedicada a brindar personal calificado para eventos, ademas de poder realizar eventos corporativos y sociales.
						<br>Contamos con personal calificado y experimentado para que tu evento salga perfecto
					</p>	
					<h5>COMUNICACIÓN CORPORATIVA Y NUEVAS TECNOLOGÍAS</h5>
					<p class="subtle">
						Presentaciones, lanzamientos de productos y marcas, roadshows, street marketing, btl, entretenimiento audiovisual con Videomapping, comunicación digital en eventos, plataforma de marketing experiencial & social media engagement, entretenimiento audiovisual (videomapping, holografías…), soluciones tecnológicas de control de asistencia, aforo e identificación.
					</p>
					<h5>EVENTOS CORPORATIVOS PRIVADOS</h5>
					<p class="subtle">
						Presentaciones, lanzamientos de productos y marcas, roadshows, street marketing, btl, entretenimiento audiovisual con Videomapping, comunicación digital en eventos, plataforma de marketing experiencial & social media engagement, entretenimiento audiovisual (videomapping, holografías…), soluciones tecnológicas de control de asistencia, aforo e identificación.
					</p>
					<h5>EVENTOS DEPORTIVOS CORPORATIVOS Y PRIVADOS</h5>
					<p class="subtle">
						Organización de eventos y torneos deportivos y organización de carreras populares…
					</p>
			</article>	
		</section>			
	</main>
</template>
<style>
	
	section{
		width: 100%;
		padding:20px;
		float: left;
	}
	.caption{
		width:100%;
		float: left;
		position: absolute;
		right: 0;
		bottom: 0;
		z-index: -1;
		opacity: 30%;
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
	article{
		width: 70%;
		margin: 0 0 0 30px;
		justify-content: center;
	}
	h2{
        text-align: left;
        color: #00ffab;
        font-size: 28px;
        padding: 20px;
		border: 20px;
    }
	h5{
        background: #00ffab;
		text-align: left;
        color: black;
        font-size: 18px;
        padding: 0 0 0 20px;
	}
	p{
		padding: 0 0 0 50px;
		color: white;
	}
</style>
