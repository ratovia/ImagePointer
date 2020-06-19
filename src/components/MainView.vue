<template>
  <div id="wrapper">
    <img id="pointer-image" src="../assets/pointer.png" alt="pointer-image">
  </div>
</template>

<script>
</script>

<style>
  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }

  #wrapper {
    height: 100vh;
    width: 100vw;
    overflow: hidden;
    
  }

  #pointer-image {
    height: 100%;
    width: 100%;
    -webkit-app-region: drag
  }
</style>
