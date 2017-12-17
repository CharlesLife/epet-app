<template>
  <div class="top">
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
  </div>
</template>

<script>
  export default {
    data () {
      return {
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="stylus" rel="stylesheet/stylus">
.top
  .header
    position fixed
    top 0
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
  #indexbox
    position fixed
    top 0
    z-index 10
    .indexheader
      height 86px
      .indexnavcon
        .headerbox
          .main
            .clearfix
              position relative
              padding 5px 10px
              width 375px
              height 51px
              .epet-search
                padding: 8px 0;
                width 355px
                height 41px
                background: #fff;
                text-align: center;
                .location
                  width 80px
                  height 22px
                  font-size 14px
                  float left
                .search-text
                  flex 1
                .epet-category
                  img
                    position absolute
                    top 10px
                    right 5px
                    width 35px
                    height 25px

            .find_nav
              overflow hidden
              width 375px
              height 35px
              ul
                width 525px
                li
                  float left


</style>
