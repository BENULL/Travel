<template>
  <swiper :options="swiperOption">
    <swiper-slide>I'm Slide 1</swiper-slide>
    <swiper-slide>I'm Slide 2</swiper-slide>
    <div class="swiper-pagination"  slot="pagination"></div>
  </swiper>
</template>
<script>
export default {
  name: 'HomeSwiper',
  data () {
    return {
      swiperOption: {}
    }
  }
}
</script>

<style lang="stylus" scoped>
</style>
