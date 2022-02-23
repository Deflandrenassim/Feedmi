<template>
  <div>
    <h3>{{ Cuisine }}</h3>
    <div class="container">
      <div class="container-row">
        <div class="mon-image">
          <img
            src="@/assets/cuisine/asiatique.jpg"
            alt="nourriture assiatique"
          />
          <span class="texte"> Asiatique </span>
        </div>
        <div class="mon-image">
          <img
            src="@/assets/cuisine/couscous.jpg"
            alt="nourriture assiatique"
          />
          <span class="texte"> Couscous </span>
        </div>
        <div class="mon-image">
          <img
            src="@/assets/cuisine/espagnole.jpg"
            alt="nourriture assiatique"
          />
          <span class="texte"> Espagnole </span>
        </div>
      </div>
      <div class="images-2">
        <div class="mon-image">
          <img src="@/assets/cuisine/halal.jpg" alt="nourriture assiatique" />
          <span class="texte"> HALLAL </span>
        </div>
        <div class="mon-image">
          <img src="@/assets/cuisine/healthy.jpg" alt="nourriture assiatique" />
          <span> Healthy </span>
        </div>
        <div class="mon-image">
          <img src="@/assets/cuisine/italien.jpg" alt="nourriture assiatique" />
          <span class="texte"> Italien </span>
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

<style>
.h3 {
  text-align: center;
  font-size: 40px;
}
.container {
  display: flex;
  justify-content: center;

}
</style>