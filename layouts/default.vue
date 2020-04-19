<template lang="pug">

#layout
  #layout_footer.flex.y_center.x_sb
    //- Anykey.eXpert
    p © 2020 Anykey.eXpert 
      
    div
      //- span.blink _> 
      a(
        href="https://chat.whatsapp.com/IjMFGwBS3ZnArTe7VqE6gm"
      ) WhatsApp

      a.mx-3(
        href="https://t.me/joinchat/AGrzUxpLIxO-2vYeBcqxlA"
      ) Telegram
  #layout_main 
    <nuxt />
    Footer
//-
  #layout
    #layout_main
      <nuxt />
    footer#layout_footer.flex.y_center.x_sb
      //- Anykey.eXpert
      p © 2020
        span.blink _ >
      div
        a(
          href="https://chat.whatsapp.com/IjMFGwBS3ZnArTe7VqE6gm"
        ) WhatsApp

        a.mx-3(
          href="https://t.me/joinchat/AGrzUxpLIxO-2vYeBcqxlA"
        ) Telegram


</template>

<demo lang="stylus">
#layout_TopNav {
  position: fixed;
  left: 0;
  top: 0;
  width: 100%;
  z-index: 10;
  color: #fff;
  padding: 1em;
  background-color: #000;
  font-family: 'Courier';
}
</demo>

<script>
import Footer from '~/components/Footer.vue'

export default {
  components: {
    Footer
  }
}
</script>

<style>
.blink {
  animation: blink 1s linear infinite;
}
@keyframes blink {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

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
  padding: 1em;
  /* background-image: radial-gradient(
    at 300px 300px,
    rgba(159, 0, 191, 0.9) 0,
    #4d4fa7 70%
  ); */
  /* background-color: #000;
  color: #fff; */
  /* box-shadow: 0px 10px 30px rgba(0, 0, 0, 0.1); */
  box-shadow: 0 5px 5px 0 rgba(0, 0, 0, 0.2);
  font-family: 'Courier';

  /* color: lime; */
}
#layout_footer a {
  color: lime;
}
</style>
