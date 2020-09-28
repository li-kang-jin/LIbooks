<template>
  <div id="app">
    <div class="box"></div>
    <h1 class="text">hello word</h1> 
    <router-view/>
  </div>
</template>

<script>


</script>
<style lang='scss' scoped>
@import "./assets/style/global";
.box{
  width:  px2rem(375);
  height: 5rem;
  background-color: brown;
}
.text{
  font-family :'Days One';
  font-size: px2rem(20);
  color: orangered;
}
</style>