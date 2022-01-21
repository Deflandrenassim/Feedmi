<template>
  <div id="app">
      
    <div class="container">

      <div class="row">
      <img
        src="@/assets/images/feedmi-logo.png"
        class="logo-feedmi"
        alt="Logo de feedmi"
      />
      <nav class="Navbar">
        <router-link to="/" class="choix"> Accueil </router-link> 
        <router-link to="/about" class="choix"> Qui somme nous </router-link> 
       <button> <router-link to="/Connexion" class="choix"> Connexion </router-link> </button>
      </nav>

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
  margin : 0px;
}
.row{
  display: flex;
  flex-direction: row;
  padding-right: 15px;
    padding-left: 15px;
    margin-right: auto;
    margin-left: auto;
  
}
.Navbar{
 
    display: flex;
    align-items: center;
    
}
.choix{
  padding: 20px;
}
.logo-feedmi{
  height: 100px;
  width: 200px;
}
#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a:hover {
  color: #42b983;
}
</style>
