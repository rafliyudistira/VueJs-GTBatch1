<template>
  <div>
       <div class="navbar-light bg-light mt-5 p-5">
      <h5 class="ml-5"><b>Complete Your Room</b></h5>
      <h5 class="ml-5"><b>With What We Designed</b></h5>
    </div>
    <div class="varian d-flex justify-content-around">
      <CardComponent cardTitle="Cangkir Mauttie" cardPrice="89.300.000" cardImage="chair-1"></CardComponent>
      <CardComponent cardTitle="Samman Kakka" cardPrice="14.500.000" cardImage="chair-2"></CardComponent>
      <CardComponent cardTitle="Lino Dino" cardPrice="22.000.000" cardImage="chair-3"></CardComponent>
      <CardComponent cardTitle="Syail Ammeno" cardPrice="12.000.000" cardImage="chair-4"></CardComponent>

    </div>
  </div>
</template>

<script>
import CardComponent from'./CardComponent.vue';

export default {
  name: 'SliderComponent',

  components: {
    CardComponent
  }
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>

