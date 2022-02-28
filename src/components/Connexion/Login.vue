<template>
  <div>
   <h3 class="animate__animated animate__backInDown"> {{inscrit }} </h3>
   <div id="container-card">
       <div class="container-form">
      <form class="formulaire">
        <div class="nom"> 
          <span> Nom : </span>
          <label for="name"></label>
          <input type="text" id="name" name="user_nom" />
        </div>
        <div class="prenom ">
          <span> Prénom : </span>
          <label for="name"></label>
          <input type="text" id="name" name="user_prenom" />
        </div>
        <div class="email">
          <span> Email : </span>
          <label for="mail"></label>
          <input type="email" id="mail" name="user_mail" />
        </div>
        <div>
          <button class="valider">Validez</button>
        </div>
      </form>
    </div>
   </div>
   
  </div>
</template>

<script>
export default {
  name: "Login",
  data() {
    return{
      inscrit: 'Inscris-toi pour ne rien rater'
    }
  }
};
</script>

<style>
h3{
  display: flex;
  justify-content: center;
  font-size: 30px;
}
#container-card{
  display:flex;
  justify-content: center;
}
.container-form{
  display:flex;
  justify-content: center;
  background-color: rgb(219, 218, 218);
  height: 500px;
  width: 500px;
  box-shadow: #03a84e 0 0 16px;
  border-radius: 10px;
  
}
.formulaire {
  display: flex;
  flex-direction: column;
  margin:auto;
  
}

.valider {
  height: 40px;
  width: 100px;
  cursor: pointer;
  color: rgb(155, 153, 153);
  border-radius: 20px 20px;
  border: solid 1px black;
}
.valider:hover {
  background-color: rgb(0, 203, 169);
}
</style>