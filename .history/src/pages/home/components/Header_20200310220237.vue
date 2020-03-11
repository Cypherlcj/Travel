<template>
  <div class="header">
    <div class="header-left">
      <div class="iconfont back-icon">&#xe743;</div>
    </div>
    <div class="header-input">
      <div class="iconfont input-icon">&#xe8b9; 输入城市/景点/游玩主题 </div>
      
      </div>
    <div class="header-right">
      城市
      <span class="iconfont">&#xe600;</span>

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
      .back-icon
        text-align :center
        font-size : .6rem
    .header-input
      flex : 1
      line-height :.64rem
      margin-top : .12rem
      margin-bottom : .12rem
      
      background : #fff
      border-radius : .1rem
      color: #ccc
      .input-icon
        padding-left : .2rem
    .header-right
      width: 1.24rem
      float: right 
      text-align : center
</style>