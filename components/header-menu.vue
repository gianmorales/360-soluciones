<template>
  <div class="row">
    <div class="col-md-3 p-0">
      <img src="/imagenes/logo1.png" alt="">
    </div>
    <div class="col-md-9 p-0">
      <header class="img">
        <div class="col-md-12">
          <nav>
            <ul>
              <li>
                <a href="/"><button class="">Inicio</button></a>
              </li>
              <li>
                <a href="/presentacion"
                  ><button class="">Presentación</button></a
                >
              </li>
              <li>
                <a href="/"><button class="">Equipo</button></a>
              </li>
              <li>
                <a href="/servicios"><button class="">Servicios</button></a>
              </li>
              <li>
                <a href="/"><button class="">Clientes</button></a>
              </li>
              <li>
                <a href="/contacto"
                  ><button class="button">Contáctanos</button></a
                >
              </li>
            </ul>
          </nav>
        </div>
      </header>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.img {
  background-image: url("/imagenes/lovepik.png");
  background-position: end;
  background-size: contain;
  height: 70px;
}
button {
  margin: 12px 20px ;
  padding: 9px 25px;
  background-color: rgb(11, 12, 12);
  border: none;
  cursor: pointer;
  transition: all 0.3s ease 0s;
  color: #0BD3B4;
}
nav {
  height: 60px;
  float: left;
}
ul {
  list-style-type: none;
  margin: 0px;
  padding: 0px;
}
ul li {
  position: relative;
  margin: 0px;
  padding: 0px;
  float: left;
  text-align: center;
}
ul li a {
  position: relative;
  display: block;
  text-decoration: none;
}
</style>