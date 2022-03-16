<template>
  <div>
    <carousel :autoplay="true" :autoplayTimeouy="2000" :mouse-drage="true">
      <slide>
        <img
          src="@/assets/images/carte.png"
          alt="plat de restaurant"
          id="images"
        />
        <div class="position">
          <span class="livraison"> Livraison dans tous le Nord </span>
        </div>
      </slide>
      <slide>
        <img
          src="@/assets/images/plate1.png"
          alt="plat de restaurant"
          id="images"
        />
      </slide>
      <slide>
        <img
          src="@/assets/images/plate2.png"
          alt="plat de restaurant"
          id="images"
        />
      </slide>
      <slide>
        <img
          src="@/assets/images/carte.png"
          alt="plat de restaurant"
          id="images"
        />
      </slide>
      <slide>
        <img
          src="@/assets/images/plate1.png"
          alt="plat de restaurant"
          id="images"
        />
      </slide>
    </carousel>
  </div>
</template>

<script>
import { Carousel, Slide } from "vue-carousel";
export default {
  name: "Caroussel",
  components: {
    Carousel,
    Slide,
  },
};
</script>
    
<style>
#images {
  height: 350px;
  width: 100%;
}
.position {
  color: rgb(0, 203, 169);
  font-size: 30px;
  position: absolute;
  top: 40px;
  left: 40px;
}
</style>