<template>
  <div>
    <product-hero></product-hero>
    <product-info></product-info>
  </div>
</template>

<script>
import ProductHero from './components/ProductHero.vue';
import ProductInfo from './components/ProductInfo.vue';
export default {
  name: 'App',
  components: {

ProductHero,
ProductInfo
    
  }
}
</script>

<style>
*{

  padding: 0px;
  margin: 0px;
}

body{

}


</style>
