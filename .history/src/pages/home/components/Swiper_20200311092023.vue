<template>
  <div class="wrapper">
  <swiper :options="swiperOption"  >
     
    <swiper-slide v-for="item of swiperList"> 
      <img  class="swiper-img" :src="item.imgUrl" alt="">
    </swiper-slide>
    <!-- <swiper-slide>
      <img class="swiper-img" src="http://img1.qunarzz.com/sight/p0/1803/9d/9d862d8166170089a3.img.jpg_600x330_b61fe99a.jpg" alt="">
    </swiper-slide> -->
 
    <!-- Optional controls -->
    <div class="swiper-pagination"  slot="pagination"></div>
  </swiper>
  </div>
</template>

<script>
export default {
  name: 'HomeSwiper',
  data() {
    return {
      swiperOption: {
        pagination: '.swiper-pagination'
      },
      swiperList: [{
        id: '0001',
        imgUrl:'http://img1.qunarzz.com/sight/p0/1603/85/85c883189bf7293390.water.jpg_600x330_fd753eb3.jpg'
      },{
        id: '0002',
        imgUrl:'http://img1.qunarzz.com/sight/p0/1803/9d/9d862d8166170089a3.img.jpg_600x330_b61fe99a.jpg'
      }]
  }
}
}
</script>

<style lang="stylus" scoped>
.wrapper >>>.swiper-pagination-bullet-active
    background : #fff
.wrapper
  overflow hidden
  width: 100%
  height: 0
  padding-bottom: 55% 
  background : #eee
  
  .swiper-img
    width : 100%
</style>