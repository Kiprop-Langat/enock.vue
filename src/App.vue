<template>
  <nav class=" bg-slate-900 flex mx-auto justify-center items-center gap-x-2" >
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/Contact">Contact</router-link> |
    <router-link to="/Numbers">Numbers</router-link>
  </nav>
  <router-view/>
</template>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
 display: flex;
  justify-items: center;
  align-items: center;
  margin: auto;

}

nav a {
  font-weight: bold;
  color: #fff;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
