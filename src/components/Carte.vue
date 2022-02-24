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
.container-row{
  display: flex;
  flex-direction: row;
  justify-content: center;
  justify-content: space-evenly;
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

</style>