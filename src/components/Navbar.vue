<template>
  <!-- Desktop -->
  <nav class="navbar fixed-top navbar-expand-xl bg-light">
    <div class="container">
      <router-link class="navbar-brand" to="/"
        ><img src="../assets/logo.png" alt="logo Elemes ID"
      /></router-link>

      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNavAltMarkup"
        aria-controls="navbarNavAltMarkup"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav m-auto">
          <router-link class="nav-link" to="/">Home</router-link>
          <router-link class="nav-link" to="/">About</router-link>
          <router-link class="nav-link" to="/"
            >Promotion<span
              class="position-absolute top-25 start-500 translate-middle badge rounded-pill bg-danger"
              >Hot
            </span></router-link
          >
          <router-link class="nav-link" to="/">Blogs</router-link>
          <router-link class="nav-link" to="/">Contact Us</router-link>
        </div>
        <div class="d-flex">
          <router-link class="btn" to="/">Masuk</router-link>
          <router-link class="btn tombol" to="/">Daftar Sekarang</router-link>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style></style>
