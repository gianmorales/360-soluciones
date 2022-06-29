<template>
  <div>
    <div class="row mt-5 d-flex justify-content-center">
      <div class="col-md-5 pt-5 pb-5 colorfondo">
        <div class="row">
          <div class="col-md-12 d-flex justify-content-center">
            <h2 class="text-center">POSTULANTES REGISTRADOS</h2>
          </div>
          <div class="col-md-12 text-center">
            <span
              >Si tiene una cuenta, inicie sesión con tu dirección de correo
              electrónico.</span
            >
          </div>
          <div class="row d-flex justify-content-center mt-3">
            <div class="form-floating mb-3 mt-3 col-md-11">
              <div class="form-floating">
                    <input
                      type="email"
                      class="form-control"
                      id="floatingInput"
                      placeholder="name@example.com"
                    >
                    <label for="floatingInput">Email</label>
                  </div>
            </div>
            <br >
            <div class="form-floating col-md-11 mt-3">
              <div class="form-floating">
                      <input
                        type="password"
                        class="form-control"
                        id="floatingPassword"
                        placeholder="Password"
                      >
                      <label for="floatingPassword">Contraseña</label>
                    </div>
            </div>
            <div class="col-md-11 mt-4">
              <button type="button" class="btn btn-danger">
                INICIAR SESIÓN
              </button>
            </div>
            <div class="row mt-3 d-flex justify-content-center">
              <div class="col-md-4 text-success">
                <hr >
              </div>
              <div class="col-md-3">
                <strong>O ingresa con</strong>
              </div>
              <div class="col-md-4 text-success">
                <hr >
              </div>
            </div>
            <redes-sociales></redes-sociales>
          </div>
        </div>
      </div>
      <div class="col-md-5 pt-5 pb-5 colorfondo">
        <div class="row">
          <div class="col-md-12 d-flex justify-content-center">
            <h2 class="text-center">NUEVOS POSTULANTES</h2>
          </div>
          <div class="col-md-12 text-center">
            <span>Si no cuentas con una cuenta, toma paso a registrarte.</span>
          </div>
          <div class="row d-flex justify-content-center mt-2">
            <div class="col-md-7 mt-4">
              <a href="/registrate"><button type="button" class="btn btn-danger">REGISTRATE</button></a>
            </div>
            <div class="row mt-3 d-flex justify-content-center">
              <div class="col-md-3 text-success">
                <hr >
              </div>
              <div class="col-md-3">
                <strong>O ingresa con</strong>
              </div>
              <div class="col-md-3 text-success">
                <hr >
              </div>
            </div>
            <div class="row d-flex justify-content-center">
                <div class="col-md-10">
                <redes-sociales ></redes-sociales>
            </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.colorfondo {
  background-color: #eee;
}
h2 {
  color: #e33127;
}
button {
  width: 100%;
  border-radius: 30px;
}
a{
  text-decoration: none;
  color: white;
}
</style>