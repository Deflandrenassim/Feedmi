<template>
  <div>
<h1> hello </h1>
<form  method="post" class="formulaire ">
    <div>
        <label for="name">Nom :</label>
        <input type="text" id="name" name="user_name">
    </div>
     <div>
        <label for="name">Prénom :</label>
        <input type="text" id="name" name="user_name">
    </div>
    <div>
        <label for="mail">e-mail:</label>
        <input type="email" id="mail" name="user_mail">
    </div>
   <div>
     <button> Validez </button>
   </div>
</form>
  </div>
</template>

<script>
export default {
    name:'Login'
}
</script>

<style>
.formulaire{
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>