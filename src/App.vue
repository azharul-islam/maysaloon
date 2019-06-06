<template>
  <div id="app">
    <img src="./assets/letterhead.png" width="700"/>
<!--    <nav id="nav">-->

<!--      <router-link to="/">Home</router-link>-->
<!--      <router-link to="/about">Products</router-link>-->
<!--      <router-link to="/about">Contact</router-link>-->
<!--      <router-link to="/about">About</router-link>-->
<!--    </nav>-->
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

  body {margin: 0;
    background-color: #f5f5f5;}

</style>
