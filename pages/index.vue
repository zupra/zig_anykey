<template lang="pug">
div

  h2.text_x5.center Наши партнеры
  .clients-grid
    img(
      v-for="img in ['288.jpg','4560.jpg','Бардак.jpg','Дом_Кафе.jpg','Компот.jpg','Кружка.jpg','МаПицца.png','Оджахури.jpg','Пилпили.png','Рикису.png','Bjorn.jpg','Bolshoi.png','BoraBora.png','CureBar.jpg','Ess-Thetik.png','Fresh.jpg','Lari.jpg','LookCafe.jpg','LureMe.jpg','Megobari.png','Piccola_Italia.jpg','Vаниль.png','Zagorami.jpg']"
      :src="require(`@/static/clients_logo/x240q80_${img}`)"
    )





</template>

<script>
// import Logo from '~/components/Logo.vue'

export default {
  components: {
    // Logo
  }
}
</script>

<style>
.clients-grid {
  padding: 2em;
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
  /* grid-template-rows: repeat(auto-fill, minmax(180px,1fr)); */
  grid-auto-flow: dense;
  grid-gap: 20px;
  align-items: center;
}
.clients-grid img {
  width: 100%;
}

/* .clients-grid_item {
} */
</style>
