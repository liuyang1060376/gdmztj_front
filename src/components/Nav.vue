<template>
  <div id="nav">
    <div class="nav-wrapper container">
      <div class="row">
        <div class="col-lg-2 logo-wrapper">
          <img src="http://www.mztj.cn/images/logo.jpg" alt="">
        </div>
        <div class="col-lg-4 search-wrapper">
          <form action="">
            <input type="text" placeholder="体检套餐/最新优惠">
          </form>
        </div>
        <div class="col-lg-6">6</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
name: "Nav"
}
</script>

<style scoped lang="stylus" ref="stylesheet/stylus">

  #nav
    height 69px
    background-color: #1d4354
    line-height 69px
    font-size 14px
    color #fffff
    .nav-wrapper
      .row
        .logo-wrapper img
          width 104px
          height 30px
          overflow hidden
        .search-wrapper
          form
            display block
            position relative
            input
              height 40px
              width 100%
              border none
              background: url("./../assets/search.png") no-repeat
              background-size: 20px 20px;
              background-position: 11px 9px
              background-color: #336278
              outline none
              border-radius 20px
              padding-left 40px
            input::placeholder
                    color #fff
                    font-weight 700










</style>
