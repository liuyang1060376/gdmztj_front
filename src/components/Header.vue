<template>
  <div id="header">
    <header class="container">
        <div class="row">
          <div class="col-md-3 h-left">
            <p>欢迎进入民众体检官网!</p>
          </div>
          <div class="col-md-3 h-middle">
            <ul>
              <li> <i class="iconfont">&#xe6b9;</i> <a href="">官方微博</a></li>
              <li><a href="">官方微信</a></li>
            </ul>
          </div>
          <div class="col-md-6 h-right">
            <ul>
              <li><a href="">在线咨询/预约</a></li>
              <li><a href=""></a>qq在线</li>
              <li><a href=""></a>手机查报告</li>
              <li><a href="">最新招聘</a></li>
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
  header
      font-size: 14px;
      color: #707070;
    .container
      row
      .h-middle
        ul li
            float left
            margin-right 10px
            padding-left 20px
            background: url("")





</style>
