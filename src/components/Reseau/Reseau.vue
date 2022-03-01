<template>
<div>
      <h4>{{ reseau }} </h4>
  <div class="container-logo">
      <div class="logo">
        <i class="fa-brands fa-instagram"></i>
        <i class="fa-brands fa-facebook"></i>
        <i class="fa-brands fa-github"></i>
        <i class="fa-brands fa-twitter"></i>
     </div>
  </div>
</div>
</template>

<script>
export default {
        name:'Reseaux',
        data(){
          return{
            reseau: '#Mes réseaux ou me joindre'
          }
        }
}
</script>

<style>
h4{

}
.container-logo{
   position: relative;
  bottom: 100px; 
}

.logo{
    display: flex;
    justify-content: space-around;
    cursor: pointer;
}
</style>