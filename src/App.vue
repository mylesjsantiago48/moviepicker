<template> 
  <div id="app"><br>
    <router-link to="/"><h1>Movie Picker</h1></router-link>
    <hr>
    <div id="nav">

    </div>
    <router-view/>
    <br>

  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
#h1{
  color: blue;
}
</style>
