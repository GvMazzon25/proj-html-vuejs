<template>
  <header>
      <Nav />
      <HadBanner />
  </header>
</template>

<script>
import Nav from '@/components/Nav.vue'
import HadBanner from '@/components/HadBanner.vue'

export default {
    name:'Header',
    components: {
        Nav,
        HadBanner,
    }
}
</script>

<style lang='scss'>
@import '@/style/header.scss';
</style>