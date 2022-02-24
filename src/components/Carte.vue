<template>
  <div>
    <h3>{{ Cuisine }}</h3>
    <div class="container">
      <div class="container-row">
        <!-- container 1 des mes image en row  -->
        <div class="mon-image">
          <img
            src="@/assets/cuisine/couscous.jpg"
            alt="nourriture assiatique"
          />
          <div class="plat"> Plat couscous </div>
        </div>

        <div class="mon-image">
          <img
            src="@/assets/cuisine/asiatique.jpg"
            alt="nourriture assiatique"
          />
         <div class="plat"> Plat couscous </div>
        </div>


        <div class="mon-image">
          <img
            src="@/assets/cuisine/italien.jpg"
            alt="nourriture assiatique"
          />
          <div class="plat"> Plat Italien </div>
        </div>

        <div class="mon-image">
          <img
            src="@/assets/cuisine/healthy.jpg"
            alt="nourriture assiatique"
          />
          <div class="plat"> Plat healthy </div>
        </div>
      </div>


      <div class="container-row">  <!-- container2 des mes image en row  -->
       
        <div class="mon-image">
          <img
            src="@/assets/cuisine/couscous.jpg"
            alt="nourriture assiatique"
          />
          <div class="plat"> Plat couscous </div>
        </div>

        <div class="mon-image">
          <img
            src="@/assets/cuisine/asiatique.jpg"
            alt="nourriture assiatique"
          />
         <div class="plat"> Plat couscous </div>
        </div>


        <div class="mon-image">
          <img
            src="@/assets/cuisine/italien.jpg"
            alt="nourriture assiatique"
          />
          <div class="plat"> Plat Italien </div>
        </div>

        <div class="mon-image">
          <img
            src="@/assets/cuisine/healthy.jpg"
            alt="nourriture assiatique"
          />
          <div class="plat"> Plat healthy </div>
        </div>
      </div>
        <div id="Svg-container">

      <svg xmlns="http://www.w3.org/2000/svg" class="svg" viewBox="0 0 1440 320">
  <path fill="#00cba9" fill-opacity="1" d="M0,288L48,272C96,256,192,224,288,197.3C384,171,480,149,576,165.3C672,181,768,235,864,250.7C960,267,1056,245,1152,250.7C1248,256,1344,288,1392,304L1440,320L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"></path>
</svg>
        </div>
       
        
    
    </div>
  </div>
</template>

<script>
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
#Svg-container{
  width: 100%;
}
.container-row{
  display: flex;
  flex-direction: row;
  justify-content: center;
  justify-content: space-evenly;
  padding-bottom: 25px;
  flex-wrap: wrap;
}
h3 {
  padding-bottom: 10px;
  display: flex;
  justify-content: center;
}

img {
  cursor: pointer;
  
}
.plat {
  display: flex;
  align-items: center;
}
.svg{
  width: 100%;
}

</style>