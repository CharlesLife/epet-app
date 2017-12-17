<template>
  <div class="main">
    <mt-swipe :auto="4000" class="mt-swipe">
      <mt-swipe-item><img src="./1轮播/c01.jpg" alt=""></mt-swipe-item>
      <mt-swipe-item><img src="./1轮播/c02.jpg" alt=""></mt-swipe-item>
      <mt-swipe-item><img src="./1轮播/c03.jpg" alt=""></mt-swipe-item>
      <mt-swipe-item><img src="./1轮播/c04.jpg" alt=""></mt-swipe-item>
      <mt-swipe-item><img src="./1轮播/c05.png" alt=""></mt-swipe-item>
      <mt-swipe-item><img src="./1轮播/c06.jpg" alt=""></mt-swipe-item>
    </mt-swipe>
    <div class="columnnavdiv">
      <ul>
        <li><img src="./E宠团/1-1.jpg" alt=""></li>
        <li><img src="./E宠团/1-2.jpg" alt=""></li>
        <li><img src="./E宠团/1-3.jpg" alt=""></li>
        <li><img src="./E宠团/1-4.jpg" alt=""></li>
        <li><img src="./E宠团/1-5.jpg" alt=""></li>
        <li><img src="./E宠团/2-1.jpg" alt=""></li>
        <li><img src="./E宠团/2-2.jpg" alt=""></li>
        <li><img src="./E宠团/2-3.jpg" alt=""></li>
        <li><img src="./E宠团/2-4.jpg" alt=""></li>
        <li><img src="./E宠团/2-5.jpg" alt=""></li>
      </ul>
    </div>
    <split></split>
    <div class="surprise_day">
      <div class="surprise-tit">
        <div class="suprice"><img src="//static.epetbar.com/static_web/wap/src/images/suprice.png" alt=""></div>
        <div class="next">距离下一场</div>
        <div class="time">00:00:00</div>
        <div class="more"><img src="https://img2.epetbar.com/nowater/2016-10/26/20/c6b7ac04e8c6cb827365c17bd74aef59.png" alt=""></div>
      </div>
      <div class="surprise-pro">
        <ul>
          <li><img src="https://img1.epetbar.com/2016-04/15/10/b239deb132f99a092e85dcc389da48ea.jpg@!300w-b" alt=""></li>
          <li><img src="https://img1.epetbar.com/2016-04/15/10/b239deb132f99a092e85dcc389da48ea.jpg@!300w-b" alt=""></li>
          <li><img src="https://img1.epetbar.com/2016-04/15/10/b239deb132f99a092e85dcc389da48ea.jpg@!300w-b" alt=""></li>
          <li><img src="https://img1.epetbar.com/2016-04/15/10/b239deb132f99a092e85dcc389da48ea.jpg@!300w-b" alt=""></li>
        </ul>
      </div>
    </div>
    <split></split>
    <div class="currency_ad">
      <img src="https://img2.epetbar.com/nowater/2017-12/13/21/ed5436e5ee13a4f8d83fff1314e24e42.jpg@!water" alt="">
    </div>
    <split></split>
    <div class="currency_ad">
      <img src="https://img2.epetbar.com/nowater/2017-12/13/21/f9b03b752970c2c957877a4c6eabf206.jpg@!water" alt="">
    </div>
    <split></split>
    <div class="custom_tite">
      <img src="https://img2.epetbar.com/nowater/2017-12/13/21/ed5436e5ee13a4f8d83fff1314e24e42.jpg@!water" alt="">
    </div>
    <split></split>
    <div class="fashion">
      <img src="https://img2.epetbar.com/nowater/2017-12/13/21/7dee954fae7fdb254a57bf9aef7fa404.jpg@!water" alt="">
    </div>
    <split></split>
    <div class="custom_tite">
      <img src="https://img2.epetbar.com/nowater/2017-12/13/21/78d0d84294183888aaaf864cb04ca0df.jpg@!water" alt="">
    </div>
  </div>
</template>

<script>
  import split from '../split/split'
  export default {
    name: "main",
    components: {
      'split': split
    }
  }
</script>

<style lang="stylus" rel="stylesheet/stylus">
.main
  .mt-swipe
    width 100%
    height 160px
    img
      width 375px
      height 160px
  .columnnavdiv
    z-index 5
    position relative
    ul
      width 375px
      height 190px
      li
        float left
        img
          width 75px
          height 95px
  .surprise_day
    position relative
    width 375px
    height 190px
    .surprise-tit
      position relative
      padding 10px
      width 375px
      height 60px
      .suprice
        float left
        img
          width 105px
          height 24px
          margin auto
          vertical-align center
      .next
        float left
        line-height 20px
        text-align center
        font-size 13px
      .time
        float left
        margin-top 5px
        margin-left 5px
        line-height 20px
      .more
        float right
        line-height 20px
        img
          width 67px
          height 40px
    .surprise-pro
      ul
        width 370px
        height 130px
        overflow hidden
        li
          float left
          img
            width 98px
            height 130px


  .currency_ad
    img
      width 375px
      height 190px
  .custom_tite
    img
      width 375px
      height 190px
  .fashion
    img
      width 375px
      height 190px
</style>
