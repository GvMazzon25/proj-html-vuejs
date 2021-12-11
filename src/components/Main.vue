<template>
  <div class="contain">
    <Section1 />
    <Section2 />
  </div>
</template>

<script>
import Section1 from '@/components/Section1.vue'
import Section2 from '@/components/Section2.vue'

export default {
  name:'Main',
  components:{
    Section1,
    Section2,
  }
}
</script>

<style lang='scss'>
@import '@/style/main.scss'; 
</style>