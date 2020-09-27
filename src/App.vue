<template>
  <div id="app">
    <div class="box"></div>
    <h1 class="text">hello word</h1> 
    <router-view/>
  </div>
</template>

<script>


</script>
<style scoped>
.box{
  width: 5rem;
  height: 5rem;
  background-color: brown;
}
.text{
  font-family :'Days One';
  font-size: 1rem;
  color: orangered;
}
</style>