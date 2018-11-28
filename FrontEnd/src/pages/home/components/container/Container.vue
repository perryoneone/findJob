<template>
  <div>
    <container-header></container-header>
    <container-body></container-body>
    <container-recommend></container-recommend>
    <hot-company></hot-company>
  </div>
</template>

<script>
import ContainerHeader from './components/Header'
import ContainerBody from './components/Body'
import ContainerRecommend from './components/Recommend'
import HotCompany from './components/HotCompany'
export default {
  name: 'HomeContainer',
  components: {HotCompany, ContainerRecommend, ContainerBody, ContainerHeader}
}
</script>

<style scoped>

</style>
