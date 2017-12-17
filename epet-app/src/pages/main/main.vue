<template>
  <div>
    <epet-header></epet-header>
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
        <div class="surprise-pro" ref="wrapper">
          <ul>
            <li>
              <img src="https://img1.epetbar.com/2016-08/30/10/1158f70a54550d8d411811976d07413b.jpg@!300w-b" alt="">
              <span class="left">￥</span>
              <span class="right">3.5</span>
              <p>省￥11.52</p>
            </li>
            <li>
              <img src="https://img1.epetbar.com/2016-12/23/16/6bcfa8ef7aafb638b358f6d345b8cd38.jpg@!300w-b" alt="">
              <span class="left">￥</span>
              <span class="right">3.5</span>
              <p>省￥11.52</p>
            </li>
            <li>
              <img src="https://img1.epetbar.com/2015-09/12/16/84a72431d0cea2db5af6354c8c039304.jpg@!300w-b" alt="">
              <span class="left">￥</span>
              <span class="right">3.5</span>
              <p>省￥11.52</p>
            </li>
            <li>
              <img src="https://img1.epetbar.com/2016-11/04/16/40d58d743b4d20777619d97d09056205.jpg@!300w-b" alt="">
              <span class="left">￥</span>
              <span class="right">3.5</span>
              <p>省￥11.52</p>
            </li>
          </ul>
        </div>
      </div>
      <split></split>
      <div class="titmoudle">
        <div class="titmoudle_left"><img src="https://img2.epetbar.com/nowater/2017-12/13/13/11acf905ca327ed7aae8f9b4851850a0.jpg" alt=""></div>
        <div class="titmoudle_right"><img src="https://img2.epetbar.com/nowater/2017-12/13/14/36046f2f89b3825c77b70ac89f5c7ad2.jpg" alt=""></div>
      </div>
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
      <split></split>
      <div class="titmoudle">
        <div class="titmoudle_left"><img src="https://img2.epetbar.com/nowater/2017-12/13/14/41be554ac711057efbb82403f8618b72.jpg" alt=""></div>
        <div class="titmoudle_right"><img src="https://img2.epetbar.com/nowater/2017-12/13/14/36046f2f89b3825c77b70ac89f5c7ad2.jpg" alt=""></div>
      </div>
      <mt-swipe :auto="4000" class="mt-swipe">
        <mt-swipe-item><img src="./2轮播/1.png" alt=""></mt-swipe-item>
        <mt-swipe-item><img src="./2轮播/2.jpg" alt=""></mt-swipe-item>
        <mt-swipe-item><img src="./2轮播/3.jpg" alt=""></mt-swipe-item>
        <mt-swipe-item><img src="./2轮播/4.jpg" alt=""></mt-swipe-item>
      </mt-swipe>
      <div class="wap-footer-bar">
        <div class="ft">
          <span>触屏版</span>
          <span>手机客户端</span>
          <span>关于我们</span>
          <span>联系我们</span>
        </div>
        <div class="copy">&copy wap.epet.com 版权：重庆易宠科技有限公司</div>
      </div>
    </div>
  </div>
</template>

<script>
  import split from '../split/split'
  import BScroll from 'better-scroll'
  import header from '../header/header'
  export default {
    components: {
      'split': split,
      'epet-header': header
    },
    mounted() {
      new BScroll(this.$refs.wrapper, {
        scrollX: true
      })
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
  .titmoudle
    position relative
    padding 10px
    height 73px
    display block
    .titmoudle_left
      float left
      img
        width 187px
        height 73px
    .titmoudle_right
      float right
      img
        width 60px
        heigh 50px
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
      width 375px
      height 130px
      ul
        width 520px
        height 130px
        overflow hidden
        content: "";
        display: block;
        clear: both
        li
          float left
          width 98px
          height 130px
          margin-right 10px
          .left
            margin-left 15px
            text-align center
            color red
            width 84px
            height 20px
            font-size 12px
          p
            margin-left 15px
            font-size 12px
          img
              width 84px
              height 84px



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
  .wap-footer-bar
    width 375px
    height 86px
    text-align center
    background #fff
    margin 30px auto
    .ft
      padding 15px 0 5px
      text-align center
      font-size 14px
      span
        padding 0 6px
      :nth-child(1)
        color red
    .copy
      text-align:center;
      margin: 10px auto;
      padding-bottom:25px;
      font-size:12px
</style>
