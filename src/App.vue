<template>
  <div id="app">
      <!-- Le header a été reparti sur App cpour facilité mon routeur sur le header -->
      <div class="row">
      <img
        src="@/assets/images/feedmi-logo.png"
        class="logo-feedmi"
        alt="Logo de feedmi"
      />
      <nav class="Navbar">
        <router-link to="/" class="choix"> ACCUEIL  </router-link> 
       <button class="btn-connexion"> <router-link to="/Connexion" class="choix"> CONNEXION </router-link> </button>
      </nav>
      
      </div>

     <transition name="fade" mode="out-in"> <!-- transition entre les pages move -->
    <router-view/>
    </transition>
    </div>

</template>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #000000;
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
  color: black;
  padding: 30px;
  outline: none;
  text-decoration: none;
}
.choix:hover{
  color: rgb(0, 203, 169);
}
.logo-feedmi{
  height: 85px;
  width: 150px;
  padding-left: 100px;
}
.btn-connexion{
  background-color: #04aa86;
  padding: 5px 10px 5px 10px;
  color: white;
  border-radius: 15px;
}
.fade-enter, .fade-leave-to {
  opacity: 0;
  transform: translateX(2em)
}
.fade-enter-active, .fade-leave-active{
  transition: all .3s ease;
}

</style>
