<template>
  <div class="header">
    <div class="header-left">
      <span class="iconfont">&#xe743;</span>
    </div>
    <div class="header-input">
      <span class="iconfont">&#xe8b9;输入城市/景点/游玩主题</span>
      </div>
    <div class="header-right">
      <span class="iconfont">&#xe600;城市</span>

      </div>
  </div>
</template>

<script  >
export default{
  name: 'HomeHeader'
    }
</script>

<style lang="stylus" scoped>

  .header 
    display : flex
    line-height: .86rem
    background : #00bcd4
    color: #fff
    .header-left
      width: .64rem
      float :left
    .header-input
      flex : 1
      line-height :.64rem
      margin-top : .12rem
      margin-left .2rem
      
      background : #fff
      border-radius : .1rem
      color: #ccc
    .header-right
      width: 1.24rem
      float: right 
      text-align : center
</style>