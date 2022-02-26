<template>
  <div>
    <h1>hello</h1>
    <div class="container-form">
      <form class="formulaire">
        <div>
          <span> Nom : </span>
          <label for="name"></label>
          <input type="text" id="name" name="user_name" />
        </div>
        <div>
          <span> Prénom : </span>
          <label for="name"></label>
          <input type="text" id="name" name="user_name" />
        </div>
        <div>
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
  background-color: Grey;
  height: 500px;
  width: 500px;
}
.formulaire {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.valider {
  height: 40px;
  width: 100px;
  cursor: pointer;
  color: grey;
  border-radius: 20px 20px;
}
.valider:hover {
  background-color: rgb(0, 203, 169);
}
</style>