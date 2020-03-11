<template>
  <swiper :options="swiperOption"  >
     
    <swiper-slide> 
      <img src="http://img1.qunarzz.com/sight/p0/1603/85/85c883189bf7293390.water.jpg_600x330_fd753eb3.jpg" alt="">
    </swiper-slide>
    <swiper-slide>
      <img src="" alt="">
    </swiper-slide>
 
    <!-- Optional controls -->
    <div class="swiper-pagination"  slot="pagination"></div>
     
  
  </swiper>
</template>

<script>
export default {
  name: 'HomeSwiper',
  data() {
    return {
      swiperOption: {}
  }
}
}
</script>

<style lang="stylus" scoped>

</style>