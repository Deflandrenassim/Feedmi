<template>
  <div>
    <carousel>
      <slide>
      <img src="@/assets/images/carte.png" alt="plat de restaurant"  id="images"/>
      </slide>
      <slide>
      <img src="@/assets/images/plate1.png" alt="plat de restaurant"  id="images" />
      </slide>
      <slide>
     <img src="@/assets/images/plate2.png" alt="plat de restaurant" id="images" /> 
     </slide>
    </carousel>
  </div>
</template>

<script>
import { Carousel, Slide } from 'vue-carousel';
export default {
  name: "Caroussel",
  components: {
      Carousel,
      Slide
  },
  methods : {
 slide() {
     let i = 0;
     let time = 2000;
     console.log(i , time);
 }
  }
}

</script>
    
<style>
#images{
  height: 100px;
  width: 100px;
}
</style>