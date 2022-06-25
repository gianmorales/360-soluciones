<template>
  <div class="row d-flex justify-content-center">
    <div class="col-md-11">
      <div class="row d-flex justify-content-end">
        <div class="col-md-10">
          <header-menu></header-menu>
        </div>
      </div>
      <main>
        <nuxt></nuxt>
      </main>
      <div class="buttonsmain">
        <a href="/vitrina"
          ><button type="button" class="btn btn-info">
            Vitrina de Talentos
          </button></a
        >
        <a href="/registrate"
          ><button type="button" class="btn btn-info">
            Registra tus datos
          </button></a
        >
      </div>
    </div>
    <div class="col-md-12">
      <footer-menu></footer-menu>
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
body {
  display: grid;
  background: black;
}
</style>