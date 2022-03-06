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
  background-color: #42b983;
  color: #fff;
}
.btn-priv:hover {
  background-color: #26a76c;
  color: #fff;
}
.jumbotron {
  background-color: #cae3f5;
}
body {
  background-color: #f4fefa;
}
</style>
