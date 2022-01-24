<template>
  <div class="home">
   <Caroussel />
  <HelloWorld />
  <Carte />


  </div>
</template>

<script>
// @ is an alias to /src
import Carte from '@/components/Carte.vue'
import HelloWorld from '@/components/HelloWorld.vue'
import Caroussel from '@/components/Caroussel.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    Caroussel,
    Carte
  }
}
</script>
