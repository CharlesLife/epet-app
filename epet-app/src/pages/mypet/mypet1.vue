<template>
  <div>
    <div class="login">
      <div class="headtop">
        <span class="back"><a href=""></a></span>
        <span class="register"><a href="">注册</a></span>
      </div>
      <div class="mlogo">
        <img src="//static.epetbar.com/mpet/images/login/logo.png" alt="">
      </div>
      <div class="tab">
        <span class="left">普通登录</span>
        <span class="right">手机动态密码登录</span>
        <i></i>
      </div>
    </div>
    <div class="mformBox">
      <div class="content">
        <form action="" method="post">
          <div>
            <mt-field type="tel" placeholder="手机号/邮箱/用户名" v-model="username">
            </mt-field>
            <mt-field  placeholder="请输入密码" type="password" v-model="password"></mt-field>
          </div>
        </form>
        <p><a href="">忘记密码？</a></p>
        <mt-button class="btn" type="primary" size="large">登录</mt-button>
      </div>
      <div class="other-login">
        <p>合作网登录</p>
        <span class="taobao"><a href="https://passport.epet.com/Oauth.html?type=4&returnurl=https%3A%2F%2Fwap.epet.com%2Fuser%2FUserCenter.html"></a></span>
        <span class="tengxun"><a href="https://passport.epet.com/Oauth.html?type=2&returnurl=https%3A%2F%2Fwap.epet.com%2Fuser%2FUserCenter.html"></a></span>
      </div>
    </div>
  </div>
</template>

<script>
  export default {

  }
</script>

<style lang="stylus" rel="stylesheet/stylus">
  .login
    position relative
    width 375px
    height 178px
    background url("./2ac7b0a4f0ab1e4a63819e0668d1cb39 (1).png") no-repeat
    background-size 100% 100%
    .headtop
      height: 50px;
      line-height: 50px;
      position: relative;
      .back
        float left
        display block
        margin-top 16px
        margin-left 12px
        width 22px
        height 20px
        background url("./personal-bico3.png") no-repeat
        background-size 12px 17px
      .register
        position absolute
        display block
        top 0
        width 32px
        height 50px
        right 5px
        a
          display block
          right 5px
          width 32px
          height 21px
          color #fff
          font-size 16px
          line-height 21px
    .mlogo
      width 375px
      height 84px
      text-align center
      line-height 82px
      img
        width 75px
        height 48px
        vertical-align middle
    .tab
      font-size 15px
      color #fff
      height 44px
      .left
        float left
        width 50%
        line-height 44px
        text-align center
        background-color rgba(255,255,255,0.3)
      .right
        float right
        width 50%
        line-height 44px
        text-align center
        background-color rgba(255,255,255,0.3)
      i
        display block
        width: 0;
        height: 0;
        border-left: 10px solid transparent;
        border-right: 10px solid transparent;
        border-bottom: 10px solid #fff;
        position: absolute;
        left: 22%;
        right: 0;
        top 169px

  .mformBox
    position relative
    height 400px
    .content
      position relative
      width 375px
      height 92px
      top 0
      background aquamarine
      form
        margin-bottom 10px
      .btn
        margin 10px auto
        background  #2ec975
        width 90%
      p
        display block
        color  #898989
        line-height 20px
        text-align right
        font-size 14px
        padding-right 30px
    .other-login
      position absolute
      width 375px
      height 114px
      bottom 0
      p
        text-align center
        font-size 16px
        line-height 20px
        color #d7d7d7
      .taobao
        width 50%
        height 93px
        float left
        text-align center
        a
          display block
          width 57px
          height 57px
          margin 10px auto
          background url("./login_ico4.png")
          background-size 57px 57px
      .tengxun
        width 50%
        height 93px
        float right
        text-align center
        a
          display block
          width 57px
          height 57px
          margin 10px auto
          background url("./login_ico2.png")
          background-size 57px 57px


</style>
