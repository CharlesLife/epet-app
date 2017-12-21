<template>
<div>
  <div id="nav" ref="wrapper">
    <ul>
      <li data-id="recommend">为您推荐</li>
    </ul>
  </div>
  <div id="recommend-list">
    <p>热门分类</p>
    <ul>
      <li>
        <img src="">
        <span>进口猫粮</span>
      </li>
      <li>
        <img src="">
        <span>美毛化毛</span>
      </li>
      <li>
        <img src="">
        <span>体内驱虫</span>
      </li>
      <li>
        <img src="">
        <span>强化免疫</span>
      </li>
      <li>
        <img src="">
        <span>猫砂专区</span>
      </li>
      <li>
        <img src="">
        <span>罐头湿粮</span>
      </li>
    </ul>
  </div>
</div>
</template>

<script>
  import BScroll from 'better-scroll'
  export default {
    data () {
      return {
      }
    },
    mounted() {
      new BScroll(this.$refs.wrapper, {
        scrollY: true
      })
    }
  }
</script>

<style lang="stylus" rel="stylesheet/stylus">
#nav
  width 70px
  height 600px
  float left
  ul
    width 70px
    height 700px

    li
      padding: 15px 0;
      border-bottom: 1px solid #f3f4f5;
      width: 70px;
      height: 50px;
      font-size: 13px;
      text-overflow: ellipsis;
      white-space: nowrap;
      overflow: hidden;
      text-align center
      &:first-child
        color red
#recommend-list
  width 300px
  height 320px
  float right
  padding-left 10px
  position relative
  overflow hidden
  p
    width 290px
    height 20px
    font-size 12px
    position absolute
    top 30px
  ul
    width 290px
    height 253.31px
    margin-top 50px
    li
      width 86.66px
      height 116.66px
      float left
      text-align center
      margin-right 10px
      margin-bottom 15px
      img
        width 86.66px
        height 86.66px
      span
        display inline-block
        font-size 12px

</style>
