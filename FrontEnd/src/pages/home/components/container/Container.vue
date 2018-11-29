<template>
  <div>
    <container-header></container-header>
    <container-body></container-body>
    <container-recommend></container-recommend>
  </div>
</template>

<script>
import ContainerHeader from './components/Header'
import ContainerBody from './components/Body'
import ContainerRecommend from './components/Recommend'
export default {
  name: 'HomeContainer',
  components: {ContainerRecommend, ContainerBody, ContainerHeader}
}
</script>

<style scoped>

</style>
