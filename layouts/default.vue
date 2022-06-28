<template>
  <div>
    <header-menu class="img"></header-menu>
    <main>
      <nuxt></nuxt>
    </main>
    
    <footer-menu></footer-menu>
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
body{
	display: grid;
	background: black;
}
.img{
    background-image: url("/imagenes/fondo.jpeg");
    background-position: center;
    background-size: cover;
  }

</style>