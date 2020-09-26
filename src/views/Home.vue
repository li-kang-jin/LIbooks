<template>
  <div class="home">
  <h1 class="text">hello word</h1> 
   <span class="icon-bookmark"></span>
  </div>
</template>

<script>
import Epub from 'epubjs'
global.ePub = Epub
export default {
  name: 'Home',
}
</script>
<style scoped>
.text{
  font-family :'Days One';
  font-size: 50px;
  color: orangered;
}
</style>
