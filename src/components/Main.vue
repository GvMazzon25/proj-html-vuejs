<template>
  <div class="contain">
    <div class="top-box">
        <div>^</div>
        <div class="tp">TOP</div>
    </div>
    <Section1 />
    <Section2 />
    <Section3 />
  </div>
</template>

<script>
import Section1 from '@/components/Section1.vue'
import Section2 from '@/components/Section2.vue'
import Section3 from '@/components/Section3.vue'

export default {
  name:'Main',
  components:{
    Section1,
    Section2,
    Section3,
  }
}
</script>

<style lang='scss'>
@import '@/style/main.scss'; 
</style>