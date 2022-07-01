<template>
<main>  
    <h2 class="title">Orgullos de nuestros Talentos</h2>
	<h5 class="subtle">Contamos con más de 50 colaboradores con pasión por el servicio y especialistas en sus rubros</h5>

    <section class="fichero">
        <div class="card" style="width: 18rem;">
            <img src="/imagenes/T1.png" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Mozos</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                </div>
        </div>

         <div class="card" style="width: 18rem;">
            <img src="/imagenes/T2.png" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Bartenders</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                </div>
        </div>

        <div class="card" style="width: 18rem;">
            <img src="/imagenes/T3.png" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Chef</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                </div>
        </div>

        <div class="card" style="width: 18rem;">
            <img src="/imagenes/T4.png" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Pastelero</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                </div>
        </div>

        <div class="card" style="width: 18rem;">
            <img src="/imagenes/T5.png" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Stewards</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                </div>
        </div>

        <div class="card" style="width: 18rem;">
            <img src="/imagenes/T6.png" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Wedding Planner</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                </div>
        </div>

        <div class="card" style="width: 18rem;">
            <img src="/imagenes/T7.png" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Supervisor</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                </div>
        </div>
        <div class="card" style="width: 18rem;">
            <img src="/imagenes/T8.png" class="card-img-top" alt="...">
                <div class="card-body">
                    <h5 class="card-title">Fotógrafos</h5>
                    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                </div>
        </div>
    </section>
</main>
</template>
<script>
export default {
  layout: "botones",
};
</script>
<style>

    .fichero{
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        margin-bottom: 100px;
    } 

    .card{
        padding: 2px 2px 2px 2px;
        margin: 20px;
        gap: 5px;
    }
    .card-title{
        font-size: 30px;
    }
    
    .subtle{
        text-align: center;
        color: white;
        font-size: 18px;
        padding: 0;
    }
   
    h2{
        text-align: center;
        color: #00ffab;
        font-size: 28px;
        padding: 15px 0 0 0 ;
    }

</style>
