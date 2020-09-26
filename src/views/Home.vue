<template>
  <div class="home">
   <div id="read"></div>
  </div>
</template>

<script>
import Epub from 'epubjs'
global.ePub = Epub
export default {
  name: 'Home',
  mounted () {
    this.book = new Epub('/《围城》 (七十年纪念)  钱钟书.epub')
    this.book.renderTo('read',{
      width:window.innerWidth,
      height:window.innerHeight
    }).display()
  }
}
</script>
