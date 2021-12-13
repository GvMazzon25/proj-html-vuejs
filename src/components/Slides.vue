<template>
  <div class="col-2">
        <div class="b-box">
          <section class="img-box">
            <img :src="img">
          </section>
          <section class="txt-sec">
            <h3>{{ text }}</h3>
          </section>
        </div>
  </div>
</template>

<script>
export default {
    name:'Slides',
    props: {
        img: String,
        id: String,
        text: String,
    }
}
</script>

<style lang:'scss'>
@import '@/style/section1.scss';
</style>