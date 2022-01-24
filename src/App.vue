<template>
  <div id="app">
      <!-- Le header a été reparti sur App cpour facilité mon routeur sur le header -->
    <div class="container">

      <div class="row">
      <img
        src="@/assets/images/feedmi-logo.png"
        class="logo-feedmi"
        alt="Logo de feedmi"
      />
      <nav class="Navbar">
        <router-link to="/" class="choix"> ACCUEIL  </router-link> 
        <router-link to="/about" class="choix"> QUI SOMME NOUS ? </router-link> 
       <button class="btn-connexion"> <router-link to="/Connexion" class="choix"> CONNEXION </router-link> </button>
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
  color: #000000;
  
}
.container{
  padding-right: 100px;
  padding-left: 100px;
  
}
.row{
  display: flex;
  flex-direction: row;
}
.Navbar{
  display: flex;
  align-items: center;   
  margin-left : 550px;
}
.choix{
  padding: 30px;
  outline: none;
}
.logo-feedmi{
  height: 85px;
  width: 150px;
}
.btn-connexion{
  background-color: #04aa86;
  padding: 5px 10px 5px 10px;
  color: white;
  border-radius: 15px;
}

</style>
