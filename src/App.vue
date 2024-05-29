<script>
  import AppTitle from './components/AppTitle.vue';
  import AppHero from './components/AppHero.vue';

  export default {
    name:'MyApp',
    data(){
      return{

      }
    },

    components: {
      AppTitle,
      AppHero,
    }

  }
</script>

<template>

  <header>
    <AppHero></AppHero>
  </header>
  
  <main>
    <AppTitle></AppTitle>
  </main>

  <footer>

  </footer>

</template>


<style>
  h1{
    color:gold
  }
</style>