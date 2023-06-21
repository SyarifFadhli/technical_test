<template>
  <div class="hero">
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <h1>
            Good Food Us <br />
            Good Mood
          </h1>
          <p>
            I would think that conserving our natural resources <br />
            should be a conservative position: Not to waste food, and <br />
            not to throw away a lot of the food that we buy.
          </p>
          <div class="cta">
            <router-link class="btn btn-daftar" to="/"
              >Daftar Sekarang</router-link
            >
            <router-link class="btn btn-about" to="/">About Us</router-link>
          </div>
        </div>
        <div class="col-md-6">
          <img src="../assets/img/hero.png" alt="" width="500" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<style></style>
