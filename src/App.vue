<template>
  <div>
    <header><page-header></page-header></header>
    <main><page-main></page-main></main>
    <footer><page-footer></page-footer></footer>
  </div>
</template>

<script>
import PageHeader from './components/PageHeader.vue';
import PageMain from './components/PageMain.vue';
import PageFooter from './components/PageFooter.vue';
export default {
  name: 'App',
  components: {

    PageHeader,
    PageMain,
    PageFooter
    
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
