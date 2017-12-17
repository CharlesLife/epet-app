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
                      <span class="catordog c89">猫猫站</span>
                      <span class="c89">|</span>
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
                <div class="find_nav_left dscroll">
                  <div class="find_nav_list dscroll-div">
                    <ul class="dscroll-ul">
                      <li class="dscroll-li">
                        <a href="">
<span class="rela navimg" >
<span >
<img src="" />
</span>
<span >
<img src="" />
</span>
<i></i>
</span>
                          <span class="rela" ><span></span><i></i></span>
                        </a>
                      </li>
                    </ul>
                  </div>
                </div>
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
  name: 'Header',
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
  #indexbox
    .indexheader
      .indexnavcon
        height 86px
        .main
          width 640px
          margin auto
          div
            padding 5px 10px
            .epet-search
              padding: 8px 0;
              background: #fff;
              text-align: center
              width: 100%;
            .location
              margin-right 20px
              position relative
              display block
              float left
              font-size 14px
              i
                position: absolute;
                top: 10px;
                right: -11px;
                border-width: 4px;
                font-size: 0;
                line-height: 0;
                border-style: solid solid dotted;
                border-color: #898989 transparent transparent;

            .epet-search p
              position relative
              display block
              float right
            .epet-search input
              width: 100%;
              border: 0;
              height: 25px;
              background: #e9e9e9;
              border-radius: 4px;
              color: #bcbcbc;
              text-indent: 10px;
              font-size: 13px;
              outline: 0;





</style>
