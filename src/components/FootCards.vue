<template>
  <section class="col-3 mx-h">
        <div class="logo-box">
         <img :src="img" />
         <h3>{{ title }}</h3>
        </div>
        <ul>
          <li>{{ txt1 }}</li>
          <li>{{ txt2 }}</li>
          <li>{{ txt3 }}</li>
          <li>{{ txt4 }}</li>
          <li>{{ txt5 }}</li>
          <li>{{ txt5 }}</li>
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
    }
}
</script>

<style>

</style>