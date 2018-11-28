<template>
  <div>
    <home-header></home-header>
    <home-container></home-container>
  </div>
</template>

<script>
import HomeHeader from './components/Header'
import HomeContainer from './components/container/Container'
export default {
  name: 'Home',
  components: {HomeHeader, HomeContainer}
}
</script>

<style scoped lang="stylus">

</style>
