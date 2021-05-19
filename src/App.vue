<template>
  <div id="app">
    <Title />
    <Hero />
  </div>
</template>

<script>
/* procedura standard per collegare la mia pagina-componente all'app */
import Title from '@/components/Title.vue'
import Hero from '@/components/Hero.vue'
export default {
  name: 'App',
  components: {
    Title,
    Hero,
  }
}
</script>

