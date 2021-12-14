<template>
  <section class="col-3 mx-h">
        <div class="logo-box">
         <img :src="img"
              class="img" 
         />
         <h3>{{ title }}</h3>
        </div>
        <div class="ul-box">
          <ul>
            <li>{{ txt1 }}</li>
            <li>{{ txt2 }}</li>
            <li>{{ txt3 }}</li>
            <li>{{ txt4 }}</li>
            <li>{{ txt5 }}</li>
            <li>{{ txt5 }}</li>
            <li>
              <img class="img2" :src="img2">
            </li>
          </ul>
        </div>
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

<style lang='scss'>
.mx-h{
    max-height: 400px;
    text-align: center; 
    margin-bottom: -300px;   
}
.logo-box{
    width: 300px;
    height: 40px;
    margin-bottom: 40px;
}
.img{
        width: 250px;
        height: auto; 
        object-fit: contain;
        background-repeat: no-repeat;
        background-size: contain;
        background-position: center;
}
.ul-box{
  width: 300px;
  height: 300px;
  .img2{
    width: 100%;
    height: 100%;
    object-fit: contain;
  }
}

</style>