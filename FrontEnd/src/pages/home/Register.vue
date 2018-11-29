<template>
  <div class="box" :style="{height: height}">
    <div class="container clearfix">
      <div class="complete-info"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Register',
  data () {
    return {
      height: document.documentElement.clientHeight + 'px'
    }
  },
  mounted () {
    window.addEventListener('resize', this.handleResize)
  },
  methods: {
    handleResize () {
      this.height = document.documentElement.clientHeight + 'px'
    }
  }
}
</script>

<style scoped lang="stylus">
  .box
    width: 100%
    background-color: #00b38a
    .container
      width: 1024px
      height: 100%
      margin: 35px auto 0
      margin-top: 0
      padding-bottom: 80px
      .complete-info
        width: 100%
        height: 100%
        background: #00b38a url(//www.lgstatic.com/www/static/mycenter/modules/complete-info/complete-info/img/mr_basicbg_a44f09a.png) center 0 no-repeat
        overflow: hidden
</style>
