<template>
  <div>
       <main>
      <div class="content">
        <div class="warna justify-content-between mt-3">
          <div class="box1">
            <img src="../assets/img/side-1.png" />
          </div>
          <div class="box2">
            <img src="../assets/img/side-2.png" />
          </div>
          <div class="box3">
            <img src="../assets/img/side-3.png" />
          </div>
          <div class="box4">
            <img src="../assets/img/side-1.png" />
          </div>
          <div class="box5">
            <img src="../assets/img/side-3.png" />
          </div>
        </div>

        <div class="kursi justify-content-between">
          <img id="imgParent" src="../assets/img/chair.png" alt="kursi" />
        </div>
        <div class="deskripsi mt-3">
          <h2>Chair Thatty</h2>
          <p>IDR 12.000.000</p>
          <a href="./shipping.html">
            <button class="glow-on-hover" type="submit">
              <img src="../assets/img/cart-icon.png" />Add to Chart
            </button></a
          >
          <hr />

          <h4 class="mt-3">About The Product</h4>
          <p>
            Tailored to a level of perfection synonymous with that of a Savile
            Row suit and with understarted quality in the detail, Jetty has been
            influenced by timeless 1950s style.
          </p>
          <p>
            Prividing a subtle nod to the past, Jetty also provides a perfect
            solution for the way we wprk today. A comprehensive product family,
            Jetty features a variety of elegant chairs and sofas
          </p>
        </div>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: 'GalleryComponent',
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>