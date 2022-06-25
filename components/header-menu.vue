<template>
  <div>
    <div class="row">
      <header class="img">
        <div class="col-md-12">
          <nav>
            <ul>
              <li>
                <a href="/"><button class="button">Inicio</button></a>
              </li>
              <li>
                <a href="/presentacion"
                  ><button class="button">Presentación</button></a
                >
              </li>
              <li>
                <a href="#"><button class="button">Equipo</button></a>
              </li>
              <li>
                <a href="#"><button class="button">Servicios</button></a>
              </li>
              <li>
                <a href="#"><button class="button">Clientes</button></a>
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

    <header class="sticky-top">
      <img class="logo" src="/imagenes/logo1.png" alt="logo" />
      <nav>
        <ul class="nav_links">
          <li><a href="/">Inicio</a></li>
          <li><a href="/presentacion">Presentación</a></li>
          <li><a href="#">Equipo</a></li>
          <li><a href="/servicios">Servicios</a></li>
          <li><a href="#">Clientes</a></li>
        </ul>
      </nav>
      <a class="cta" href="/contacto"
        ><button class="button">Contáctanos</button></a
      >
    </header>
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
  margin-left: 20px;
  padding: 9px 25px;
  background-color: rgba(0, 136, 169, 1);
  border: none;
  border-radius: 50px;
  cursor: pointer;
  transition: all 0.3s ease 0s;
}
nav {
  width: 100%;
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