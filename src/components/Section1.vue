<template>
  <div class="banner1">
    <div class="row">
      <Slides v-for='slide in slides'
              :key="slide"
              :img='slide.image'
              :id='slide.id'
              :txt='slide.text'
      />
    </div>  
  </div>
</template>

<script>
import Slides from '../components/Slides.vue'

export default {
 name:'Section1',
 components:{
   Slides
 },
 data() {
   return {
    slides: [
      {
        id:'1',
        image: '../assets/h5-custom-icon-1.png',
        text:'Languages',
      },
      {
        id:'2',
        img:'../assets/h5-custom-icon-2.png',
        text:'Software',
      },
      {
        id:'3',
        img:'../assets/h5-custom-icon-3.png',
        text:'Software',
      },
      {
        id:'4',
        img:'../assets/h5-custom-icon-4.png',
        text:'Software',
      },
      {
        id:'5',
        img:'../assets/h5-custom-icon-5.png',
        text:'Software',
      },
      {
        id:'6',
        img:'',
        text:'Software',
      },
    ]
   }
 },
}
</script>

<style lang='scss'>
@import '@/style/section1.scss';
</style>