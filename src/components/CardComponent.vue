<template>
  <div>
       <div class="label1">
          <div class="kursi1">
            <img id="img1" :src="require( '@/assets/img/' + cardImage + '.png')" alt="kursi"/>
          </div>
          <label class="ml-3"><b>{{ cardTitle }}</b><br />{{ cardPrice }}</label>
          <div class="card-body">
            <a href="./shipping.html" class="btn btn-primary">Beli</a>
          </div>
        </div>
  </div>
</template>

<script>
export default {
  name: 'CardComponent',
  props: [
      "cardTitle", "cardPrice", "cardImage"
  ],
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>