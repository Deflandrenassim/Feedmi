<template>
  <div class="home">
   <Caroussel />
  <HelloWorld />
  <Carte />
  <Maps />
  <Reseaux />

  </div>
</template>

<script>
// @ is an alias to /src
import Carte from '@/components/Carte.vue'
import HelloWorld from '@/components/HelloWorld.vue'
import Caroussel from '@/components/Caroussel.vue'
import Maps from '@/components/Map/Maps.vue'
import Reseaux from '@/components/Reseau/Reseau.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    Caroussel,
    Carte,
    Maps,
    Reseaux
  }
}
</script>
