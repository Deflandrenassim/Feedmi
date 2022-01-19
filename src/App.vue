<template>
  <div id="app">
    <div class="container">
      <img
        src="@/assets/images/feedmi-logo.png"
        class="logo-feedmi"
        alt="Logo de feedmi"
      />
      <div class="nav">
        <router-link to="/" class="choix"> Accueil </router-link>
        <router-link to="/about" class="choix"> Qui somme nous </router-link>
        <router-link to="/Connexion" class="choix"> Connexion </router-link>
      </div>
    </div>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #27333f;
}
.container{
  
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a:hover {
  color: #42b983;
}
</style>
