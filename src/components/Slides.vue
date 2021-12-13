<template>
  <div class="col-2">
        <div class="b-box">
          <section class="img-box">
            <img :src="img" />
          </section>
          <section class="txt-sec">
            <h3>{{ txt }}</h3>
          </section>
        </div>
  </div>
</template>

<script>
export default {
    name:'Slides',
    props: {
        img: String,
        txt: String,
    }
}
</script>

<style lang:'scss'>
@import '@/style/section1.scss';
</style>