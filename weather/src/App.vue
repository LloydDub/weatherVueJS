<template>
  <div id="app">
   <main>
     <div class="search-box">
       <input type="text" class="search" placeholder="Search...">
       
     </div>
   </main>
  </div>
</template>

<script>


export default {
  name: 'App',
  data () {
    return {
      api_key: '5e23803e2e209d40d32345f556ff0e96'
    }
  }

}
</script>

<style>
* {
  margin: 0;
  padding: 0;
   box-sizing: border-box; 
}

body { 
  font-family: 'montserrat', sans-serif;
}

#app {
  background-image: url('./assets/cold-bg.jpg')
}
</style>
