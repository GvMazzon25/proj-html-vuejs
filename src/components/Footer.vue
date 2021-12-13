<template>
  <div class="footer">
    <div class="row">
      <FootCards v-for="(card, index) in cards"
         :key="index"
         :img="card.image"
         :title="card.title"
         :txt1="card.text1"
         :txt2="card.text2"
         :txt3="card.text3"
         :txt4="card.text4"
         :txt5="card.text5"
         :txt6="card.text6"
      />
    </div>  
    <hr>
      <div class="row end-box">
        <section class="col-6 cop"> Copirights 2017 Mikado Themes </section>
        <section class="col-6 row end">
          <div class="col-4">CALL +44 300 3030266</div>
          <div class="col-4">FOLLOW US</div>
          <div class="col-4 row">
            <div class="col-4"><i class="fa-brands fa-twitter"></i></div>
            <div class="col-4"><i class="fa-brands fa-instagram"></i></div>
            <div class="col-4"><i class="fa-brands fa-facebook-f"></i></div>
          </div>
        </section>
      </div>
  </div>
</template>

<script>
import FootCards from '../components/FootCards';

export default {
  name:'Footer',
  component:{
    FootCards,
  },
   data() {
    return {
      cards: [
        {
          image:'',
          text1:'',
          text2:'',
          text3:'',
          text4:'',
          text5:'',
          text6:'',
        },
        {
          title:'',
          text1:'',
          text2:'',
          text3:'',
          text4:'',
          text5:'',
          text6:'',
        },
        {
          title:'',
          text1:'',
          text2:'',
          text3:'',
          text4:'',
          text5:'',
        },
        {
          title:'',
          image:''
        }
        
      ]
    }
  }
}
</script>

<style lang='scss'>
@import '../style/footer.scss';
</style>