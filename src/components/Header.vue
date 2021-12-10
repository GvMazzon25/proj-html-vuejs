<template>
  <header>
      <Nav />
  </header>
</template>

<script>
import Nav from '@/components/Nav.vue'

export default {
    name:'Header',
    components: {
        Nav,
    }
}
</script>

<style lang='scss'>
@import '@/style/header.scss'
</style>