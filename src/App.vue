<template>
 <div id="app">
    <div class="navbar-container">
      <div class="navbar-content">
      <router-link to="/">
        <i class="bx bx-home-heart bx-sm"></i>
      </router-link>

         <router-link to="/cart">
        <i class="bx bx-cart bx-sm"></i>
        </router-link>
         <router-link to="/favoritos">
        <i class='bx bxs-heart bx-sm' ></i>
        </router-link>
         <router-link to="/historial">
        <i class='bx bx-history bx-sm' ></i>
         </router-link>
       </div>
    </div>
    <router-view/>
  </div>
</template>



<style lang="less">
@import url('https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@300&display=swap');
.navbar-container {
width: 100%;
position: fixed;
bottom: 0;
  .navbar-content{
    padding: 15px;
    
    display: flex;
    justify-content: space-between;
    a {
      color: rgb(163, 163, 163);
      &.router-link-exact-active {
      color: rgb(255, 131, 62);
    }
    }
    

  }
}



#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
*{
  margin:  0px;
  padding: 0px;
}



</style>
