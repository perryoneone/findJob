<template>
  <div class="header">
    <div class="search-wrapper">
      <div class="search-box">
        <form action="/search" method="get" class="search-form" >
          <input type="text" id="search_input" class="search_input" placeholder="搜索职位、公司或地点" autocomplete="off" maxlength="64" tabindex="1" />
          <input type="submit" name="" id="search_btn" class="search_btn" value="搜索">
        </form>
      </div>
      <div class="guess-wrapper"></div>
      <div class="hot-search"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ContainerHeader'
}
</script>

<style scoped lang="stylus">
  .header
    position: relative
    .search-wrapper
      background-color: #f2f5f4
      padding: 30px 0 28px
      min-width: 1200px
      .search-box
        border: 0 solid #00b38a
        width: 938px
        height: 46px
        margin: 0 auto
        position: relative
        .search_input
          width: 762px
          height: 20px
          line-height: 20px
          float: left
          font-size: 16px
          padding: 12px 16px
          margin: 0
          border: 1px solid #E8E8E8
          border-right: 0
        .search_btn
          float: left
          width: 142px
          height: 46px
          font-size: 18px
          color: #FFF
          border: 0
          background: #00b38a
          cursor: pointer
</style>
