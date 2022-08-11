<template>
  <nav class="navbar">
    <h1 class="titletext">JRT</h1>
    
  </nav>
  <div class="routerlinks">
    <router-link to="/">Home</router-link> | 
    <router-link to="/about">About</router-link> | 
    <router-link to="/projects">Projects</router-link>
   
  </div>
  
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

.navbar {
  background: linear-gradient(-90deg, rgb(132, 207, 106), rgb(22, 192, 176));
}

.routerlinks {
  text-align: right;
  position: relative;
  bottom: 90px;
  margin-right: 10px;
}

.titletext {
  font-size: 30px;
  color: black;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  text-align: left;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
