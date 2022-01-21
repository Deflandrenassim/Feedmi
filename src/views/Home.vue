<template>
  <div class="home">
   <Caroussel />
  <HelloWorld />

  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Caroussel from '@/components/Caroussel.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    Caroussel
  }
}
</script>
