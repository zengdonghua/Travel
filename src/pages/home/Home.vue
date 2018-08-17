<template>
  <div>
    <header-view></header-view>
    <swiper-view></swiper-view>
  </div>
</template>

<script>

import HeaderView from './components/Header'
import SwiperView from './components/Swiper'
export default{
  name: 'Home',
  components: {
    HeaderView,
    SwiperView
  }
}
</script>

<style>

</style>
