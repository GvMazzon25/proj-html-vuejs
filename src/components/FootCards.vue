<template>
  <section class="col-3 mx-h">
        <div class="logo-box">
         <img :src="img"
              class="img" 
         />
         <h3>{{ title }}</h3>
        </div>
        <ul>
          <li>{{ txt1 }}</li>
          <li>{{ txt2 }}</li>
          <li>{{ txt3 }}</li>
          <li>{{ txt4 }}</li>
          <li>{{ txt5 }}</li>
          <li>{{ txt5 }}</li>
          <img :src="img2">
        </ul>
      </section>
</template>

<script>
export default {
  name:'FootCards',
  props: {
        img: String,
        title: String,
        txt1: String,
        txt2: String,
        txt3: String,
        txt4: String,
        txt5: String,
        txt6: String,
        img2: String,
    },
}
</script>

<style lang:'scss'>
.logo-box{
    width: 100%;
    height: 40px;
    margin-bottom: 20px;
}
.img{
        width: 100%;
        height: 100%; 
        object-fit: contain;
        background-repeat: no-repeat;
        background-size: contain;
        background-position: center;
    }
</style>