<template>
  <div class="home">
   <Caroussel />
  <HelloWorld />
  <Carte />
  <Maps />


  </div>
</template>

<script>
// @ is an alias to /src
import Carte from '@/components/Carte.vue'
import HelloWorld from '@/components/HelloWorld.vue'
import Caroussel from '@/components/Caroussel.vue'
import Maps from '@/components/Map/Maps.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    Caroussel,
    Carte,
    Maps
  }
}
</script>
