<template>
  <div class="header">
    <div class="back iconfont">&#xe632;</div>
    <div class="seach iconfont">
      &#xe632;请输入城市
    </div>
    <div class="point">
      上海
      <span class="san"></span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexHeader'
}
</script>

<style lang="stylus" scoped>
  .header
    display:flex
    height:.88rem
    background: #03bbd4
    .back
      width:.6rem
      height:.88rem
      font-size:.38rem
      text-align:center
      line-height:.88rem
      color: #fff
    .seach
      flex: 1
      height:.6rem
      background: #fff
      padding-left:.2rem
      margin:.14rem .2rem
      border:1px solid #03bbd4
      border-radius: 4px
      text-align:left
      line-height:.6rem
      font-size:.33rem
      color:#e3e7ea
    .point
      width:1.1rem
      height:.88rem
      text-align:left
      line-height:.88rem
      color:#fff
      .san
        width: 0
        height: 0
        position:relative
        top:.22rem
        border-left: .1rem solid transparent
        border-right: .1rem solid transparent
        border-top: .18rem solid #fff
</style>
