<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
 export default {
  data(){
    return{
      name: 'Katia'
    }
  },
  components: {
    AppTitle,
    AppHero
  }
    
 }
</script>


<template>
  <app-title></app-title>
  <app-hero></app-hero>

</template>


<style>

</style>
