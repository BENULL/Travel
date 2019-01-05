<template>
  <div class="header">
    <div class="header-left">返回</div>
    <div class="header-input">输入城市/景点/游玩主题</div>
    <div class="header-right">城市</div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
 .header
  display: flex
  line-height: .86rem
  color: #ffffff
  background: #00bcd4
  .header-left
    float: left
    width: .64rem
  .header-input
    flex: 1
    height: .64rem
    line-height: .64rem
    margin-left: .2rem
    margin-top: .12rem
    background: #ffffff
    border-radius: .1rem
    color: #cccccc
  .header-right
    width: 1.24rem
    float: right
    text-align: center

</style>
