

<script>
// H1
import AppTitle from './components/AppTitle.vue';
import Jumbotron from './components/Jumbotron.vue';

export default {
  components:{
    AppTitle,
    Jumbotron
  }
}

</script>

<!-- src/App.vue -->
<template>
  

  <section>
   

    <div id="app">
      <AppTitle />

      <Jumbotron
      title="Questo è un jumbotron"
      subtitle=""
      description=""
      buttonText="Learn more"
      :buttonLink="'https://example.com'"
      />
      
    </div>
  </section>
    
</template>

<style>
/* Puoi aggiungere i tuoi stili qui o lasciare vuoto */
</style>
