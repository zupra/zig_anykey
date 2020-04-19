<template lang="pug">
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
    'main'
    'footer';
}

#layout_main {
  grid-area: main;
  overflow-y: auto;
  -webkit-overflow-scrolling: touch;
}

#layout_footer {
  grid-area: footer;
  color: #fff;
  padding: 1em;
  /* background-image: radial-gradient(
    at 300px 300px,
    rgba(159, 0, 191, 0.9) 0,
    #4d4fa7 70%
  ); */
  background-color: #000;
  font-family: 'Courier';

  color: lime;
}
#layout_footer a {
  color: lime;
}
</style>
