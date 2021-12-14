<template>
  <div class="footer">
    <div class="row first-sec">
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
         :img2="card.image2"
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
import FootCards from '../components/FootCards.vue';

export default {
  name:'Footer',
  components: {
    FootCards,
  },
   data() {
    return {
      cards: [
        {
          image:'../assets/footer-logo-1.png',
          text1:'Providing Life Changing',
          text2:'Experiences Through',
          text3:'Education. Class That Fit Your',
          text4:'Busy Life. Closer to Home',
          text5:'1-677-124-44227',
          text6:'Mon-Sat 8.00-18.00',
        },
        {
          image:'',
          title:'Popular Courses',
          text1:'Buisness English',
          text2:'Preston Marshall',
          text3:'Social Computing',
          text4:'David Sanders',
          text5:'Learn Spanish',
          text6:'Jennie King',
        },
        {
          image:'',
          title:'Support',
          text1:'User Dashboard',
          text2:'Contact Us',
          text3:'FAQ',
          text4:'Course Offer',
          text5:'Everits',
        },
        {
          title:'Flexible Learning',
          image2:'../assets/footer-img-1.png'
        }
        
      ]
    }
  }
}
</script>

<style lang='scss'>
@import '../style/footer.scss';
</style>