<template lang="pug">

#layout
  #layout_footer.flex.y_center.x_sb
    b ANYKEY.EXPERT

    //- svg(width='58', height='44')
    //-   rect(x='14', y='6', width='30', height='32', fill='rgba(255, 255, 255, .5)', stroke='gold', stroke-width='2')
    //-   g(stroke='grey', stroke-width='4')
    //-     path(d='M5,14 L32,14')
    //-     path(d='M5,22 L26,22')
    //-     path(d='M5,30 L20,30')
    //-   polyline(points='50,10 36,22 50,34', fill='grey')
      
    //- 
      a.mx-3(
        href="https://chat.whatsapp.com/IjMFGwBS3ZnArTe7VqE6gm"
      ) WhatsApp

      a(
        href="https://t.me/joinchat/AGrzUxpLIxO-2vYeBcqxlA"
      ) Telegram
  #layout_main 
    <nuxt />
    Footer

</template>

<script>
import Footer from '~/components/Footer.vue'

export default {
  components: {
    Footer
  }
}
</script>

<style>
#layout {
  display: grid;
  height: 100vh;
  overflow-x: hidden;
  grid-template-columns: auto;
  grid-template-rows: auto auto;

  grid-template-areas:
    'footer'
    'main';
}

#layout_main {
  grid-area: main;
  overflow-y: auto;
  -webkit-overflow-scrolling: touch;
}

#layout_footer {
  z-index: 10;
  grid-area: footer;
  padding: 4px;
  padding-left: 1em;

  /* background-image: radial-gradient(
    at 300px 300px,
    rgba(159, 0, 191, 0.9) 0,
    #4d4fa7 70%
  ); */
  /* background-color: #000;
  color: #fff; */
  /* box-shadow: 0px 10px 30px rgba(0, 0, 0, 0.1); */
  box-shadow: 0 5px 5px 0 rgba(0, 0, 0, 0.2);
  /* font-family: 'Courier'; */

  /* color: lime; */
}
</style>
