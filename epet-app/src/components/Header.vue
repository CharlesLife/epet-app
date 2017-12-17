<template>
  <div>
    <div class="header">
      <div class="overflow xiazaiApp">
        <div class="overflow rela">
        <span class="clsoebtn">
          <img id="close_down_bar" src="//static.epetbar.com/static_wap/lib/common_images/closebtn_03.png"/>
        </span>
          <div class="appdowimg">
            <a href="" style="display: block;">
              <img src="https://img2.epetbar.com/nowater/2017-12/13/18/c63b6e6cf483cbb61196f658920a9d6e.jpg@!water" />
            </a>
          </div>
        </div>
      </div>
    </div>
    <div id="indexbox" class="main">
      <div class="indexheader">
        <div class="indexnavcon">
          <div class="headerbox float-div">
            <div class="main">
              <div class="clearfix pt5 pl10 pr10 pb5">
                <div class="epet-search bgf">
                  <div class="fl rela ft14 location">
                    <a href="">
                      <span class="catordog c89">猫猫站|</span>
                      <span data-name="my-place" class="myposition c89 ft13">重庆</span>
                      <i></i>
                    </a>
                  </div>
                  <p class="search-text">
                    <a href="">
                      <input type="search" placeholder="搜索商品和品牌" disabled="">
                      <span class="eico serach-ico"></span>
                    </a>
                  </p>
                  <a href='' class="epet-category">
                    <img src="//static.epetbar.com/static_web/wap/src/images/mydope.png">
                  </a>
                </div>
              </div>
              <div class="find_nav">
                <ul>
                  <li>首页</li>
                  <li>猫猫主粮</li>
                  <li>罐头超市</li>
                  <li>医疗保健</li>
                  <li>猫砂</li>
                  <li>零食玩具</li>
                  <li>美容香波</li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="banner_item" >
        <div>

        </div>
      </div>
    </div>
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
    <div class="currency_ad">

    </div>
    <div class="currency_ad">

    </div>
    <div class="custom_tite">

    </div>
    <div class="fashion">

    </div>
    <div class="custom_tite">

    </div>
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
</template>

<script>
  export default {
    name: 'header',
    data () {
      return {
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="stylus" rel="stylesheet/stylus">
  .header
    .xiazaiApp
      width: 100%
      margin 0 auto
      .rela
        position: relative
        .clsoebtn
          position absolute
          display inline-block
          width 5%
          margin-right 2%
          vertical-align middle
          top 20%
          left 2%
          img
            width 100%

        .appdowimg
          img
            width 100%

  .wap-footer-bar
    width 375px
    height 86px
    text-align center
    .copy
      text-align:center;
      margin:0 10px 0 10px;
      padding-bottom:25px;
      font-size:12px

</style>
