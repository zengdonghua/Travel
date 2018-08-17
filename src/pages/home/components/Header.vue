<template>
  <div class="header">
    <div class="header-left">
      <span class="iconfont">&#xe624;</span>
    </div>
    <div class="header-input">
      <span class="iconfont">&#xe632;</span>
      <input type="text">
    </div>
    <div class="header-right">
      <span class="city">城市</span>
      <span class="iconfont city-all">&#xe64a;</span>
    </div>
  </div>
</template>

<script>
export default{
  name: 'Header'
}
</script>

<style lang="stylus" scoped>
@import '~styles/varibles.styl'
.header
  display: flex
  height: .86rem
  background: #00bcd4
  color: #fff
  .header-left
    width: .64rem
    float: left
    position: relative
    span
      position: absolute
      top: 50%
      left: 50%
      transform: translate(-50%,-50%)
      font-size: .4rem
  .header-input
    flex: 1
    height: .64rem
    margin: .12rem 0 0 .2rem
    background: #fff
    border-radius: .1rem
    color: #ccc
    padding-left: .1rem
    position relative
    span
      position absolute
      top:.1rem
      font-size: .45rem
    input
      margin .1rem 0 0 .5rem
      width: 90%
  .header-right
    width: 1.24rem
    float: right
    margin-left: .1rem
    .city
      line-height: 0.86rem
    .city-all
      font-size: .24rem
</style>
