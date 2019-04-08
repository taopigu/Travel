<template>
  <div class="header">
    城市选择
      <router-link to="/">
        <div class="header-left"><div class="iconfont header-back">&#xe624;</div></div>
      </router-link>
  </div>
</template>

<script type="text/javascript">
export default{
  name: 'CityHeader'
}
</script>

<style lang='stylus' scoped>
  @import '../..\/..\/assets\/styles\/varibles.styl'
  .header
    position: relative
    overflow: hidden
    height: $headerHeight
    line-height: $headerHeight
    text-align: center
    color: #fff
    background: $bgColor
    font-size: .4rem
    .header-back
      position: absolute
      top: 0
      left: 0
      width: .64rem
      text-align: conter
      font-size: .4rem
      color: #fff
</style>
