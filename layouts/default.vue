<template lang="pug">
#layout
  #layout_main
    <nuxt />
  footer#layout_footer.flex.y_center.x_sb
    //- Anykey.eXpert
    p © 2020
    div
      img(
        src="https://icongr.am/devicon/chrome-original.svg?size=48"
      )
      img.mx-2(
        src="https://icongr.am/devicon/chrome-original.svg?size=48"
      )
      img(
        src="https://icongr.am/devicon/chrome-original.svg?size=48"
      )

</template>

<style>
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
  background-color: #000;
  color: #fff;
  padding: 4px 1em;
  /* border-top: 1px solid #e3e5e8; */
}
</style>
