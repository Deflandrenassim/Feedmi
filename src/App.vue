<template>
  <div id="app">
    <div id="nav">
      <div class="feedmi-logo">
      <img src="@/assets/images/feedmi-logo.png" alt="Logo de feedmi" />
      </div>
      <router-link to="/" class="choix"> Accueil </router-link> 
      <router-link to="/about" class="choix"> Qui somme nous </router-link> 
      <router-link to="/Connexion" class="choix"> Connexion </router-link>
    </div>

    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
.nav {
    display: flex;
    flex-direction: row;
}
.choix{
  display: flex;
  justify-content: center;
 
  
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a:hover {
  color: #42b983;
}
</style>
