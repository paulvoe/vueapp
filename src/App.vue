<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>

export default {
  name: 'App',
  data: () => {
    return {      
    }
  },
  components: {
  },
}

</script>

<style>
body{
  margin:0;
  background-color: black;
}

#app {
  font-family: serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #FFF;
  display: flex;
  justify-content: center;
}

</style>
