<template>
  <div class="kategori">
    <div class="container">
      <h2>
        Browser Our Category <br />
        <span>Receipt</span>
      </h2>
      <div class="row text-center g-4">
        <div class="col-md-3">
          <router-link class="card-link" to="/"
            ><div class="card bg1">
              <div class="card-body">
                <img src="../assets/img/Frame.png" alt="" />
                <h6 class="card-title">Cupcake</h6>
                <p class="card-text">22 items</p>
              </div>
            </div></router-link
          >
        </div>
        <div class="col-md-3">
          <router-link class="card-link" to="/"
            ><div class="card bg2">
              <div class="card-body">
                <img src="../assets/img/pizza.png" alt="" />
                <h6 class="card-title">Pizza</h6>
                <p class="card-text">25 items</p>
              </div>
            </div></router-link
          >
        </div>
        <div class="col-md-3">
          <router-link class="card-link" to="/"
            ><div class="card bg3">
              <div class="card-body">
                <img src="../assets/img/kebab.png" alt="" />
                <h6 class="card-title">Kebab</h6>
                <p class="card-text">12 items</p>
              </div>
            </div></router-link
          >
        </div>
        <div class="col-md-3">
          <router-link class="card-link" to="/"
            ><div class="card bg4">
              <div class="card-body">
                <img src="../assets/img/salmon.png" alt="" />
                <h6 class="card-title">Salmon</h6>
                <p class="card-text">22 items</p>
              </div>
            </div></router-link
          >
        </div>
        <div class="col-md-3">
          <router-link class="card-link" to="/"
            ><div class="card bg5">
              <div class="card-body">
                <img src="../assets/img/doughnut.png" alt="" />
                <h6 class="card-title">doughnut</h6>
                <p class="card-text">11 items</p>
              </div>
            </div></router-link
          >
        </div>
      </div>
      <div class="previous d-flex justify-content-end">
        <router-link class="btn tombol" to="/"
          ><i class="bi bi-arrow-left-circle-fill"></i> PREV</router-link
        >
        <router-link class="btn tombol" to="/"
          >NEXT <i class="bi bi-arrow-right-circle-fill"></i
        ></router-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Kategori",
};
</script>

<style></style>
