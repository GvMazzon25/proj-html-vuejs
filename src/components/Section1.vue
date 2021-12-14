<template>
  <div class="banner1">
    <div class="row">
      <Slides v-for="(slide, index) in slides"
        :key="index"
        :img="slide.image"
        :txt="slide.text"
      />
    </div>  
  </div>
</template>

<script>
import Slides from '../components/Slides.vue'

export default {
 name:'Section1',
 components: {
   Slides
 },
 data() {
   return {
    slides: [
      {
        image:'../assets/h5-custom-icon-1.png',
        text:'Languages',
      },
      {
        image:'../assets/h5-custom-icon-2.png',
        text:'Software',
      },
      {
        image:'../assets/h5-custom-icon-3.png',
        text:'Buisness',
      },
      {
        image:'../assets/h5-custom-icon-4.png',
        text:'Chemistry',
      },
      {
        image:'../assets/h5-custom-icon-5.png',
        text:'Science',
      },
      {
        image:'../assets/h5-custom-icon-6.png',
        text:'DIY&Crafts',
      },
    ]
   }
 },
}
</script>

<style lang='scss'>
@import '@/style/section1.scss';
</style>