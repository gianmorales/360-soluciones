<template>
<div>


  <div class="root row d-flex justify-content-center">
    <div class="col-md-12">
      <div class="row d-flex justify-content-end">
        <div class="col-md-12">
          <header-menu></header-menu>
        </div>
      </div>
      <main>
        <nuxt></nuxt>
      </main>
      
    </div>
    <div class="col-md-12">
      <div class="buttonsmain">
        <nuxt-link to="/terminos-y-condiciones"
          ><button type="button" class="btn btn-info">
            Términos y Condiciones
          </button></nuxt-link>
        <nuxt-link to="/trabaja-con-nosotros"
          ><button type="button" class="btn btn-info">
            Trabaja con Nosotros
          </button></nuxt-link>
      </div>
      <footer-menu></footer-menu>
    </div>
    

  </div>
</div>

</template>


<style scoped>
button {
  margin-left: 20px;
  padding: 9px 25px;
  background-color: rgba(0, 136, 169, 1);
  border: none;
  border-radius: 50px;
  cursor: pointer;
  transition: all 0.3s ease 0s;
}

button:hover {
  background-color: rgba(0, 136, 169, 0.8);
}


</style>