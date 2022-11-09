
<!-- nella sezione script creo l'istanza del componente app principale. -->
<script>
import AppTitle from "./components/AppTitle.vue"
import AppHero from "./components/AppHero.vue"

// #2 definisco una proprietá components per registrare i componenti importati al punto 1
export default {
  components: {
    AppTitle,
    AppHero
  }
}
</script>

<!-- Nella sezione template metto il markup della mia app -->
<template>
  <AppTitle />
  <AppHero />
</template>

<!-- Nella sezione style metto il css -->
<style>
/* css per il componente App */
</style>

