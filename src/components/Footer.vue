<template>
  <footer class="footer">
    <div class="container">
      <div class="footer-top">
        <div class="row">
          <div class="col-lg-4 col-md-6 footer-contact">
            <img src="../assets/logo.png" alt="logo" />
            <p>
              Jl. Prof. DR. Satrio No.7, RT.3/RW.3, Karet Kuningan, Kecamatan
              Setiabudi, Kota Jakarta Selatan, Daerah Khusus Ibukota Jakarta
              12950
            </p>
            <div class="social-links pt-3 pt-md-0">
              <router-link class="link" to="/"
                ><i class="bi bi-envelope"></i
              ></router-link>
              <router-link class="link" to="/"
                ><i class="bi bi-telephone"></i
              ></router-link>
              <router-link class="link" to="/"
                ><i class="bi bi-instagram"></i
              ></router-link>
            </div>
          </div>

          <div class="col-lg-2 col-md-6 footer-links">
            <h4>Categories</h4>
            <div class="footer-item">
              <router-link class="link" to="/">Cupcake</router-link> <br />
              <router-link class="link" to="/">Pizza</router-link><br />
              <router-link class="link" to="/">Kebab</router-link><br />
              <router-link class="link" to="/">Salmon</router-link><br />
              <router-link class="link" to="/">Dougnut</router-link>
            </div>
          </div>

          <div class="col-lg-2 col-md-6 footer-links">
            <h4>About Us</h4>
            <div class="footer-item">
              <router-link class="link" to="/">Kebab</router-link><br />
              <router-link class="link" to="/">Salmon</router-link><br />
              <router-link class="link" to="/">Dougnut</router-link>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 footer-newsletter">
            <h4>Newsletter</h4>
            <p>
              Get now free 50% discount for alll products on your first order
            </p>
            <div class="input-group mb-3">
              <input
                type="text"
                class="form-control form"
                placeholder="Your email address"
                aria-label="Your email address"
                aria-describedby="button-addon2"
              />
              <button class="btn btn-send" type="button" id="button-addon2">
                SEND
              </button>
            </div>
            <router-link class="link" to="/"
              ><i class="bi bi-envelope"></i> elemesid@gmail.com</router-link
            ><br />
            <router-link class="link" to="/"
              ><i class="bi bi-telephone"></i> 0888 1111 2222</router-link
            >
            <p></p>
            <p></p>
          </div>
        </div>
      </div>
    </div>
    <div class="container py-4">
      <div class="text-center">
        <div class="copyright">&copy; 2021 ELEMES ID. ALL RIGHTS RESERVED</div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style></style>
