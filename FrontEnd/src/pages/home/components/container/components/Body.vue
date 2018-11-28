<template>
  <div class="body">
    <Carousel :autoplay="true" v-model="value2" loop :autoplay-speed="5000">
      <CarouselItem>
        <div class="demo-carousel">
          <a href="#">
            <img src="https://www.lgstatic.com/i/image2/M01/AF/5D/CgotOVv34T2AanexAAPngDucdlk976.JPG" alt="2018雇主评选" width="840" height="346">
          </a>
        </div>
      </CarouselItem>
      <CarouselItem>
        <div class="demo-carousel">
          <a href="#">
            <img src="https://www.lgstatic.com/i/image2/M01/AF/BB/CgoB5lv6t6aABNk7AAq5yi546ok560.PNG" alt="2018雇主评选" width="840" height="346">
          </a>
        </div>
      </CarouselItem>
      <CarouselItem>
        <div class="demo-carousel">
          <a href="#">
            <img src="https://www.lgstatic.com/i/image2/M01/B0/D3/CgotOVv86GiADG-tAASjARA1_f8155.JPG" alt="2018雇主评选" width="840" height="346">
          </a>
        </div>
      </CarouselItem>
    </Carousel>
  </div>
</template>

<script>
export default {
  name: 'ContainerBody',
  data () {
    return {
      value2: 0
    }
  }
}
</script>

<style scoped lang="stylus">
  .body
    margin: 26px auto 0
    width: 840px
    .demo-carousel
      width: 840px
      height: 346px
</style>
