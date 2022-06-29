<template>
    <div>
        <div class="row d-flex justify-content-center">
              <div class="col-md-4">
                <button type="button" class="btn btn-facebook">
                  <span class="d-flex justify-content-center">
                    <svg style="width: 24px; height: 24px" viewBox="0 0 24 24">
                      <path
                        class="pb-4"
                        fill="currentColor"
                        d="M12 2.04C6.5 2.04 2 6.53 2 12.06C2 17.06 5.66 21.21 10.44 21.96V14.96H7.9V12.06H10.44V9.85C10.44 7.34 11.93 5.96 14.22 5.96C15.31 5.96 16.45 6.15 16.45 6.15V8.62H15.19C13.95 8.62 13.56 9.39 13.56 10.18V12.06H16.34L15.89 14.96H13.56V21.96A10 10 0 0 0 22 12.06C22 6.53 17.5 2.04 12 2.04Z"
                      ></path>
                    </svg>
                    FACEBOOK
                  </span>
                </button>
              </div>
              <div class="col-md-4">
                <button type="button" class="btn btn-google">
                  <span class="d-flex justify-content-center">
                    <svg
                      class="btn-google"
                      style="width: 24px; height: 24px"
                      xmlns="http://www.w3.org/2000/svg"
                      xmlns:xlink="http://www.w3.org/1999/xlink"
                      viewBox="0 0 48 48"
                    >
                      <defs>
                        <path
                          id="a"
                          d="M44.5 20H24v8.5h11.8C34.7 33.9 30.1 37 24 37c-7.2 0-13-5.8-13-13s5.8-13 13-13c3.1 0 5.9 1.1 8.1 2.9l6.4-6.4C34.6 4.1 29.6 2 24 2 11.8 2 2 11.8 2 24s9.8 22 22 22c11 0 21-8 21-22 0-1.3-.2-2.7-.5-4z"
                        ></path>
                      </defs>
                      <clipPath id="b">
                        <use xlink:href="#a" overflow="visible"></use>
                      </clipPath>
                      <path
                        clip-path="url(#b)"
                        fill="#FBBC05"
                        d="M0 37V11l17 13z"
                      ></path>
                      <path
                        clip-path="url(#b)"
                        fill="#EA4335"
                        d="M0 11l17 13 7-6.1L48 14V0H0z"
                      ></path>
                      <path
                        clip-path="url(#b)"
                        fill="#34A853"
                        d="M0 37l30-23 7.9 1L48 0v48H0z"
                      ></path>
                      <path
                        clip-path="url(#b)"
                        fill="#4285F4"
                        d="M48 48L17 24l-4-3 35-10z"
                      ></path>
                    </svg>
                    GOOGLE
                  </span>
                </button>
              </div>
            </div>
    </div>
</template>
<style scoped>
.btn-facebook {
  background-color: rgb(29, 87, 145);
  color: white;
  border-radius: 30px;
}
.btn-google {
  background-color: #66f442;
  color: white;
  border-radius: 30px;
}
</style>