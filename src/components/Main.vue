<template>
  <div class="contain">
    <Section1 />
    
  </div>
</template>

<script>
import Section1 from '@/components/Section1.vue'

export default {
  name:'Main',
  components:{
    Section1
  }
}
</script>

<style lang='scss'>
@import '@/style/main.scss'; 
</style>