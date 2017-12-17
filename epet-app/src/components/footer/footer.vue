<template>
  <div>
    <div class="wap-footer-bar">
      <div class="ft">
        <span>触屏版</span>
        <span>手机客户端</span>
        <span>关于我们</span>
        <span>联系我们</span>
      </div>
      <div class="copy">&copy wap.epet.com 版权：重庆易宠科技有限公司</div>
    </div>
    <div class="footernav">
      <ul class="footernav_ul">
        <li class="first_page"><a href=""></a></li>
        <li class="type"><a href=""></a></li>
        <li class="cart"><a href=""></a></li>
        <li class="mypet"><a href=""></a></li>
      </ul>
    </div>
  </div>
</template>

<script>
  export default {
    name: "footer"
  }
</script>

<style lang="stylus" rel="stylesheet/stylus">
  .wap-footer-bar
    width 375px
    height 86px
    text-align center
    .copy
      text-align:center;
      margin:0 10px 0 10px;
      padding-bottom:25px;
      font-size:12px

  .footernav
    position fixed
    bottom 0
    height 45px
    width 375px
    .footernav_ul
      width 100%
      height 45px
      li
        float left
        width 93px
        height 55px
        a
          display inline-block
          width 42px
          height 40px
          background url("./img.png") no-repeat


</style>
