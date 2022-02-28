<template>
  <div>
   
    <div class="container-form">
      <form class="formulaire">
        <div class="nom"> 
          <span> Nom : </span>
          <label for="name"></label>
          <input type="text" id="name" name="user_name" />
        </div>
        <div class="prenom ">
          <span> Prénom : </span>
          <label for="name"></label>
          <input type="text" id="name" name="user_name" />
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
</template>

<script>
export default {
  name: "Login",
};
</script>

<style>
.container-form{
  margin: auto;
  background-color: Grey;
  height: 500px;
  width: 500px;
  box-shadow: #03a84e 0 0 16px;
  border-radius: 10px;
  margin-top: 5%;
}
.formulaire {
  display: flex;
  flex-direction: column;
  align-items: center;
  
}
.nom, .email .prenom{
 margin: auto;
}
.valider {
  height: 40px;
  width: 100px;
  cursor: pointer;
  color: rgb(155, 153, 153);
  border-radius: 20px 20px;
}
.valider:hover {
  background-color: rgb(0, 203, 169);
}
</style>