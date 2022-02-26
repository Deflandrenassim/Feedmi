<template>
  <div>
    <h3 class="animate__animated animate__bounceInRight">{{ Cuisine }}</h3>
    <div class="container">
      <div class="container-row">
        <!-- container 1 des mes image en row  -->
        <div class="mon-image">
          <img
            src="@/assets/cuisine/couscous.jpg"
            alt="nourriture assiatique"
          />
          <div class="plat">Plat couscous</div>
        </div>

        <div class="mon-image">
          <img
            src="@/assets/cuisine/asiatique.jpg"
            alt="nourriture assiatique"
          />
          <div class="plat">Plat couscous</div>
        </div>

        <div class="mon-image">
          <img src="@/assets/cuisine/italien.jpg" alt="nourriture assiatique" />
          <div class="plat">Plat Italien</div>
        </div>

        <div class="mon-image">
          <img src="@/assets/cuisine/healthy.jpg" alt="nourriture assiatique" />
          <div class="plat">Plat healthy</div>
        </div>
      </div>

      <div class="container-row">
        <!-- container2 des mes image en row  -->

        <div class="mon-image">
          <img
            src="@/assets/cuisine/asiatique.jpg"
            alt="nourriture assiatique"
          />
          <div class="plat">Plat couscous</div>
        </div>

        <div class="mon-image">
          <img src="@/assets/cuisine/italien.jpg" alt="nourriture assiatique" />
          <div class="plat">Plat Italien</div>
        </div>

        <div class="mon-image">
          <img src="@/assets/cuisine/healthy.jpg" alt="nourriture assiatique" />
          <div class="plat">Plat healthy</div>
        </div>

        <div class="mon-image">
          <img
            src="@/assets/cuisine/couscous.jpg"
            alt="nourriture assiatique"
          />
          <div class="plat">Plat couscous</div>
        </div>
      </div>
    </div>
   
  </div>
</template>

<script>
import "animate.css";
export default {
  name: "Carte",

  data() {
    return {
      Cuisine: "Type de Cuisine ",
    };
  },
};
</script>

<style scoped>
#Svg-container {
  width: 100%;
  padding-bottom: 250px;
}
.container-row {
  display: flex;
  flex-direction: row;
  justify-content: center;
  justify-content: space-evenly;
  padding-bottom: 25px;
  flex-wrap: wrap;
}
h3 {
  font-size: 30px;
  padding-bottom: 10px;
  display: flex;
  justify-content: center;
}

img {
  cursor: pointer;
}
.plat {
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: rgb(0, 203, 169);
  border-radius: 0 8px;
  height: 40px;

  cursor: pointer;
}
.svg {
  min-width: 100%;
}
</style>