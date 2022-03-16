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
          <p class="paie">Nos moyens de paiement :</p>
          <div class="paiement">
            <i class="fa-brands fa-cc-paypal"></i>
            <i class="fa-brands fa-cc-visa"></i>
            <i class="fa-brands fa-cc-paypal"></i>
            <i class="fa-brands fa-cc-amex"></i>
          </div>
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
  position: absolute;
  top: 40px;
  left: 40px;
}
.livraison {
  font-size: 30px;
  color: rgb(0, 203, 169);
  text-decoration: underline dotted rgba(204, 184, 2, 0.692);
}
.paiement {
  display: flex;
  justify-content: space-evenly;
  padding-top: 10px;
  font-size: 40px;
}
.fa-brands {
  color: rgba(204, 184, 2, 0.692);
}
.paie {
  color: black;
  display: flex;
  justify-content: center;
}
</style>