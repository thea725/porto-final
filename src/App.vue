<template>
  <div id="app">
    <b-nav id="nav" tabs>
      <router-link to="/">Home</router-link>
      <router-link to="/contact">Contact</router-link>
      <router-link to="/project">Project</router-link>
    </b-nav>
    <router-view />
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
    margin: 0.5rem;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

.btn-priv {
  background-color: #42B983;
  color: #fff;
}
.btn-priv:hover{
  background-color: #26A76C;
  color: #fff;
}
.jumbotron {
    background-color: #CAE3F5;
}
body {
  background-color: #F4FEFA;
}
</style>
