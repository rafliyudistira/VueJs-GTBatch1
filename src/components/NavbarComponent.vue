<template>
  <div>
      <nav class="navbar navbar-light justify-content-between">
      <div>
        <img class="ml-4" src="../assets/img/logo.png" alt="" />
      </div>
      <div class="d-flex mr-4">
        <a class="nav-link text-dark" href="">Showcase</a>
        <a class="nav-link text-dark" href="">Catalog</a>
        <a class="nav-link text-dark" href="">Delivery</a>
        <a class="nav-link text-dark" href=""
          >Rewards <img src="../assets/img/cart-icon.png"
        /></a>
      </div>
    </nav>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <a class="navbar-brand" href="#"></a>
      <img src="" />
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <a class="nav-link" href="./index.html"
              >Home /<span class="sr-only">(current)</span></a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Office Room /</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Details</a>
          </li>
        </ul>
      </div>
    </nav>
    <div
      class="alert alert-warning alert-dismissible fade show d-none"
      id="alertEmail"
      role="alert"
    >
      <p class="m-0 p-0" id="textEmail"></p>
      <button type="button" class="close" id="btnClose">
        <span aria-hidden="true">&times;</span>
      </button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NavbarComponent',
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
