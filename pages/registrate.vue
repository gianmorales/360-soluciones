<template>
  <div>
    <div class="row d-flex justify-content-center pt-5">
      <div class="col-md-8 colorfondo pt-5">
        <div class="row d-flex justify-content-center">
          <div class="col-md-11">
          <nuxt-link to="/trabaja-con-nosotros">
            <svg style="width: 34px; height: 34px" viewBox="0 0 24 24">
            <path
              fill="currentColor"
              d="M2,12A10,10 0 0,1 12,2A10,10 0 0,1 22,12A10,10 0 0,1 12,22A10,10 0 0,1 2,12M18,11H10L13.5,7.5L12.08,6.08L6.16,12L12.08,17.92L13.5,16.5L10,13H18V11Z"
            />
          </svg>
          </nuxt-link>
        </div>
        </div>
        <div class="row">
          <div class="col-md-12 text-center mt-3">
            <h1>CREAR NUEVA CUENTA DE POSTULANTE</h1>
            <p class="pt-3">Te invitamos a que seas parte de 360 SOLUCIONES</p>
          </div>
        </div>
        <form action="" class="pt-3 pb-5">
          <div class="row d-flex justify-content-center">
            <div class="col-md-8">
              <div class="row">
                <div class="col-md-12 form-floating mt-3">
                  <div class="form-floating pb-4">
                    <input
                      type="text"
                      class="form-control"
                      placeholder="Nombre"
                      id="floatingTextInput"
                      name="nombre"
                    />
                    <label for="floatingTextInput">Nombre</label>
                  </div>
                </div>
                <div class="col-md-6 form-floating mt-3">
                  <div class="form-floating pb-4">
                    <input
                      type="text"
                      class="form-control"
                      placeholder="Apellido Paterno"
                      name="apPaterno"
                    />
                    <label for="floatingTextInput">Apellido Paterno </label>
                  </div>
                </div>
                <div class="col-md-6 form-floating mt-3">
                  <div class="form-floating pb-4">
                    <input
                      type="text"
                      class="form-control"
                      placeholder="Apellido Materno"
                      name="aMaterno"
                    />
                    <label for="floatingTextInput">Apellido Materno</label>
                  </div>
                </div>
                <div class="col-md-12 form-floating mt-3">
                  <div class="form-floating pb-4">
                    <input
                      type="email"
                      class="form-control"
                      id="floatingInput"
                      placeholder="name@example.com"
                    />
                    <label for="floatingInput">Email</label>
                  </div>
                  <div class="col-md-12 form-floating mt-3">
                    <div class="form-floating pb-4">
                      <input
                        type="password"
                        class="form-control"
                        id="floatingPassword"
                        placeholder="Password"
                      />
                      <label for="floatingPassword">Contraseña</label>
                    </div>
                  </div>
                  <div class="col-md-12 form-floating mt-3">
                    <div class="form-floating pb-4">
                      <input
                        type="password"
                        class="form-control"
                        id="floatingPassword"
                        placeholder="Password"
                      />
                      <label for="floatingPassword1">Confirmar Contraseña</label>
                    </div>
                  </div>
                  <div class="col-md-12 mt-4">
                    <button type="button" class="btn btn-danger">
                      INICIAR SESIÓN
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  layout: "botones",
};
</script>
<style scoped>
input {
  border-radius: 6px;
  border: 2px solid rgb(219, 132, 132);
}
.colorfondo {
  background-color: #eee;
}
h1 {
  color: #e33127;
}
.btn {
  width: 100%;
  border-radius: 30px;
}
</style>