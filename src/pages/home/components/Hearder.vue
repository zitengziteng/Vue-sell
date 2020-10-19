<template>
  <div>
    <div class="heaader">
      <div class="header-left">头部环境搭建好了 --- 111</div>
      <div class="header-input">222</div>
       <div class="header-right">333</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader',
}
</script>

<style lang="stylus" scoped>
  .header
    display: flex
    color: #ffffff
    .header-left
      width: .64rem
      float: left
    .header-input
      height: .64rem
      color: #ccc;
    .header-right
      float: right
      text-align: center
      color: #fff
</style>