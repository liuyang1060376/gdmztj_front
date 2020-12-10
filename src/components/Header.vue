<template>
  <div id="header" class="d-none d-md-block">
    <header class="container">
        <div class="row">
          <div class="col-sm-6 col-lg-2  h-left">
            <p>欢迎进入民众体检官网!</p>
          </div>
          <div class="col-lg-3 d-none d-lg-block h-middle">
            <ul>
              <li> <a href="">官方微博</a></li>
              <li><a href="">官方微信</a></li>
            </ul>
          </div>
          <div class="col-md-6 h-right">
            <ul>
              <li><a href="">最新招聘</a></li>
              <li class="spacer"></li>
              <li><a href="">手机查报告</a></li>
              <li class="spacer"></li>
              <li><a href="">qq在线</a></li>
              <li class="spacer"></li>
              <li><a href="">在线咨询</a></li>
            </ul>
          </div>
        </div>
    </header>
  </div>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped lang="stylus" ref="stylesheet/stylus">
#header
  background-color: #f1f1f1
  height 32px
  line-height 32px
  header
      font-size: 14px;
      color: #707070;
    .container
      row
      .h-middle
        ul li
            margin-right 5px
            float left
            padding-left 20px
        ul li:nth-child(2)
            background: url("./../assets/wb.png") no-repeat
            background-size: 20px 20px
            background-position: 0 6px
            a
              color #707070
              text-decoration none
        ul li:nth-child(1)
            background: url("./../assets/wx.png") no-repeat
            background-size: 20px 20px
            background-position: 0 6px
            a
              color #707070
              text-decoration none


      .h-right
        display flex
        justify-content flex-end

        ul
          li
            float left
            height 100%
            margin-right 10px
            a
              color #707070
          .spacer
            width: 1px;
            height: 15px;
            line-height 10px
            background-color: #ccc;
            margin-top 9px





</style>
