<template>
  <header>
    <img class="logo" src="/imagenes/logo1.png" alt="logo" />
    <nav>
      <ul class="nav_links">
        <li><a href="/">Inicio</a></li>
        <li><a href="/presentacion">Presentación</a></li>
        <li><a href="#">Equipo</a></li>
        <li><a href="#">Servicios</a></li>
        <li><a href="#" class="cta"><button class="button">Clientes</button></a></li>
      </ul>
    </nav>
    <a class="cta" href="/contacto"><button class="button">Contáctanos</button></a>
  </header>
</template>
<script>
export default {
};
</script>
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
</style>