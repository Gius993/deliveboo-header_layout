<template>
  <div id="app">
    <HomeUtent  />
  </div>
</template>

<script>
import HomeUtent from './components/HomeUtent.vue'


export default {
  name: 'App',
  components: {
    HomeUtent,
    
}
}
</script>

<style lang="scss">
 @import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:wght@300;400;500;700&family=Pacifico&display=swap');
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    img{
      width: 100%;
    }
    a{
      text-decoration: none;
      color: inherit;
    }
  }
  body{
    font-family: 'IBM Plex Sans', 
    sans-serif;

  }
</style>
