<template>
  <div id="nav">
    <router-link :to="{ name: 'EventList'}">Events Yeah</router-link> |
    <router-link :to="{ name: 'About'}">About</router-link>
  </div>
  <router-view />
</template>
// global styles
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
  color: pink;
}

#nav a.router-link-exact-active {
  color: deeppink;
}

h4 {
  font-size: 20px;
  color: deeppink;
}
</style>
