<template>
  <div class="nav">
    <div class="inner">
      <div class="nav_l">
        <a href="/" class="logo">
          <h1>拉钩网</h1>
        </a>
        <div class="suggestCity">
          <strong>成都站</strong>
          <em id="changeCity_btn">[切换城市]</em>
        </div>
      </div>
      <ul class="nav_wrap">
        <li>
          <a href="/" class="current">首页</a>
        </li>
        <li>
          <a href="/">公司</a>
        </li>
        <li>
          <a href="/">校园</a>
        </li>
        <li>
          <a href="/">言职</a>
        </li>
      </ul>
      <div class="nav_r">
        <ul>
          <router-link to="/login" tag="li"><a href="/login">登陆</a></router-link>
          <router-link to="/register" tag="li"><a href="/reg">注册</a></router-link>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style scoped lang="stylus">
  .nav
    height: 54px
    min-width: 1200px
    border-top: 1px solid #d2d2d2
    border-bottom: 1px solid #e5e5e5
    background-color: #fafafa
    .inner
      width: 1200px
      margin: 0 auto
      .nav_l
        float: left
        width: 260px
        .logo
          color: #555555
          background-color: transparent
          text-decoration: none
          h1
            float: left
            width: 97px
            height: 34px
            margin: 10px 0 0
            padding: 0
            font-weight: 400
            font-size: 2em
            background-image: url(//www.lgstatic.com/www/static/common/widgets/header_c/modules/img/logo_1c5763c.png)
            overflow: hidden
            text-indent: -99em
        .suggestCity
          float: left
          height: 44px
          padding: 10px 0 0 12px
          font-size: 18px
          line-height: 44px
          strong
            margin-right: 8px;
            color: #333
            font-size: 18px
            font-weight: 400
          em
            color: #999
            font-size: 12px
            cursor: pointer
      .nav_wrap
        float: left
        li
          display: inline-block
          margin: 0 16px
          position: relative
          a
            display: block
            font-size: 18px
            color: #999
            line-height: 53px
            padding: 0 5px
          a.current
            color: #333
            border-bottom: 2px solid #00b38a
      .nav_r
        ul
          float: right
          li
            position: relative
            float: left
            height: 30px
            a
              color: #c4c3c3
              float: left
              line-height: 53px
              padding: 0 12px
              font-size: 18px

</style>
