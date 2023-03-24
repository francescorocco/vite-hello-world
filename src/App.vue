<template>
  <div class="background">
    <AppHero/>
    <AppTitle/>
  </div>
  
</template>


<script>
  import AppTitle from './components/AppTitle.vue';
  import AppHero from './components/AppHero.vue';

  export default {
    components:{
      AppTitle,
      AppHero
    }
  }

  
</script>


<style>
  .background {
    height: 100vh;
    background: #e3c903;
    background: linear-gradient(0deg, #ff7700 0%, #d8dc1e 100%);
    display: flex;
    justify-content: center;
    position: relative;
  }
</style>