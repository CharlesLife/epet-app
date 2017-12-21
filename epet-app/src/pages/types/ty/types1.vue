<template>
  <div>
    <div class="tab-item">
      <div class="header-tpe">
        <div class="left">
          <span>分类</span>
        </div>
        <div class="right">
          <span>品牌</span>
        </div>
        <span class="small"></span>
        <div class="border-1px"></div>
      </div>
    </div>
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
    <div id="wrap">
      <div class="split"></div>
      <div class="title">
        <p>——主粮品牌——</p>
      </div>
      <div class="list">
        <ul>
          <li>
            <img src="" >
            <p>冠能</p>
            <p>美国</p>
          </li>
        </ul>
      </div>
      <split></split>
      <div class="title">
        <p>——主粮品牌——</p>
      </div>
      <div>
        <ul>
          <li>
            <img>
          </li>
        </ul>
      </div>
      <split></split>
      <div class="title">
        <p>——主粮品牌——</p>
      </div>
      <div>
        <ul>
          <li>
            <img>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
  import {mapState} from 'vuex'
  import split  from '../../components/split/split'
  import BScroll from 'better-scroll'
  export default {
    data () {
      return{
        isShow: true
      }
    },
    components: {
      split,
    },
    computed: {
      ...mapState(['categorys'])
    },
    mounted() {
      new BScroll(this.$refs.wrapper, {
        scrollX: true
      });
    }
  }
</script>

<style lang="stylus" rel="stylesheet/stylus">
  .header-tpe
    width 375px
    height 40px
    border-1px rgba(7, 17, 27, 0.1)
    position relative
    background: #ffffff;
    z-index 10
    .small
      position: absolute;
      left 135px
      bottom .2rem
      width 35px
      height 2px
      background: #ed4044
    .left
      width 50%
      height 40px
      text-align right;
      line-height 40px
      padding-right 5%
      float: left;
      span
        display inline-block
        padding: 0 4px;
        cursor: pointer;
        font-size: 13px;
        font-weight: 700;
        color red
      .right
        width 45%
        height 40px
        text-align left ;
        line-height 40px
        padding-left 5%
        float: left;
      span
        display inline-block
        padding: 0 4px;
        cursor: pointer;
        font-size: 13px;
        font-weight: 700;
      img
        width 14px
        height  14px
        position absolute
        top 14px
        right 14px
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

  #wrap
    box-sizing border-box
    .split
      width: 100%
      height: 5px
      border-top: 1px solid rgba(7, 17, 27, 0.1)
      border-bottom: 1px solid rgba(7, 17, 27, 0.1)
      background: #f3f4f5
    .title
      width 375px
      height 40px
      position relative
      p
        font-size 12px
        text-align center
        color #999
        position absolute
        bottom 0
        left 140px
    .list
      width 365px
      height 508px
      ul
        width 100%
        height 100%
        li
          width 121.64px
          height 107px
          float left
          padding-top 30px
          text-align center
          margin-bottom 15px
          img
            width 65%
            margin-left 12px
          :nth-child(2)
            font-size 13px
            color #333
            margin-top 18px
            margin-left 10px
          :nth-child(3)
            font-size 12px
            color #999
            margin-top 6px
            margin-left 10px

</style>
