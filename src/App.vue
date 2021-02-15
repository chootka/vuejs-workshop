<template>
  <div id="app">
    
    <nav>
      <router-link to="/">Home</router-link>
      <router-link to="works">Works</router-link>
    </nav>

    <router-view></router-view>

  </div>
</template>

<script>

export default {
  name: 'App'
}
</script>

<style>
@font-face {
  font-family: "NokiaPureH";
  src: url("~@/assets/fonts/NokiaPureHWeb_Rg.otf") format("truetype");
}
@font-face {
  font-family: "NokiaPureHLt";
  src: url("~@/assets/fonts/NokiaPureHWeb_Lt.otf") format("truetype");
}
@font-face {
  font-family: "NokiaPureHBold";
  src: url("~@/assets/fonts/NokiaPureHWeb_Bd.otf") format("truetype");
}

#app {
  font-family: NokiaPureH, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 20px;
}

nav {
  display: flex;
  justify-content: center;
  margin: 0 auto;
}

nav a {
  padding: 10px;
}

</style>
