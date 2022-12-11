<!-- 
Create un nuovo progetto utilizzando Vite: 
aiutatevi con le slide per ripercorrere i vari passaggi 
dell’installazione come visti a lezione.

Create e utilizzate un componente AppTitle,

il quale contiene un titolo che recita 
“La mia prima app con Vite!”
Bonus:
Creare un secondo componente AppHero, 
che visualizza un jumbotron. -->












<script>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'
export default {
  // name: "APP",
  components: {
    AppTitle,
    AppHero
  }
}
</script>

<template>

  <AppTitle />
  <AppHero />


</template>

<style scoped>

</style>
