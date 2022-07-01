<template>
  <div class="row">
    <div class="col-md-3 p-0">
      <img src="/imagenes/logo1.png" alt="" />
    </div>
    <div class="col-md-9 p-0">
      <header class="sticky-top">
        <div class="col-md-12">
          <nav>
            <ul>
              <li>
                <nuxt-link to="/">
                  <button class="button">INICIO</button>
                </nuxt-link>
              </li>
              <li>
             
                <nuxt-link to="/presentacion">
                  <button class="button">PRESENTACIÓN</button>
                </nuxt-link>
              </li>
              <li>
                <nuxt-link to="/equipo"><button class="button">EQUIPO</button></nuxt-link>
              </li>
              <li>
                <nuxt-link to="/servicios"
                  ><button class="button">SERVICIOS</button></nuxt-link>

              </li>
              <li>
                <nuxt-link to="/clientes"><button class="button">CLIENTES</button></nuxt-link>
              </li>
              <li>
                <nuxt-link to="/contacto"
                  ><button class="button">CONTÁCTANOS</button></nuxt-link>
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
button {
  margin: 12px 20px;
  padding: 9px 25px;
  background-color: rgb(139, 192, 192);
  border: none;
  cursor: pointer;
  transition: all 0.3s ease 0s;
  color: white;
  border-radius: 10px;
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