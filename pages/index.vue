<template lang="pug">
div

  .grid
    .item-a
      //- .text_x3 anykey expert
      //- h1.text_x5Автоматизация ресторанов баров и кафе

      h1.text_x5 ЕГАИС
        br
        | R-Keeper
        br
        | StoreHouse
        br
        | ККМ по 54-ФЗ
    .item-b.white.bold
      .text_x3.mb-3 Автоматизация ресторанов баров и кафе
      .text_x2 Digital audits, facilitated design thinking workshops, digital strategy development, campaign and website analytics, user research, content strategy development, user scenarios and persona development and media strategy.
      //- img(
      //-   style="width: 100%;"
      //-   :src="require(`@/static/fallout/fallout-robot.png`)"
      //- )
    .item-c
      //- h1.mb-3 item-c
      .bold_900.mb-1.text_x5 На связи 24/7
      .mb-2.text_x4 8(495)199-57-89
      .mb-3 Если у вас возникла срочная проблема, которая останавливает работу заведения
      .mb-3 У нас всегда дежурят 2 IT-пециалиста. Вы можете им звонить круглосутчно в любой день, включая праздники и выходные.

      .mb-3 Настройка удаленного рабочего места
      p Быстро и безопасно
    .item-d
      h1.mb-3 item-d
      p В подвале телефон  - 8(495)199-57-89 и кнопка заказать звонок (клик - всплывающая форма телефон и имя и, наверное, необязательным полем с “краткая информация по вопросу”)
    .item-e
      h1.mb-3 item-e
      p.mb-3 Digital audits, facilitated design thinking workshops, digital strategy development, campaign and website analytics, user research, content strategy development, user scenarios and persona development and media strategy.
    .item-f.white
      h1.mb-3 item-f
      p.mb-3 Digital audits, facilitated design thinking workshops, 
    .item-g
      h1.mb-3 item-g
      p.mb-3 Digital audits, facilitated design thinking workshops, digital strategy development, campaign and website 
      p.mb-3 Digital audits, facilitated design thinking workshops, digital strategy development, campaign and website analytics, user research, content strategy development, user scenarios and persona development and media strategy.
      h4 Blanditiis nisi commodi illo
    .item-h
      h1.mb-3 item-h
      .text_s1.mb-3 Digital audits, facilitated design thinking workshops, digital strategy development, campaign and website analytics, user research
      .mt-4.text_x2 Blanditiis nisi commodi illo
      h2.text_s2 facilitated design thinking workshops, digital strategy development
    .item-i
      h1.mb-3 item-i
      p.mb-3 Digital audits, facilitated design thinking workshops, 

  .clients
    h2.text_x5.center.mb-3 Наши партнеры
    .clients_grid
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

<style lang="stylus">
img {
  display: inline-block;
  width: 100%;
}

.clients {
  background-color: #fffff9;
  padding: 2.2em 1.4em;

  &_grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
    /* grid-template-rows: repeat(auto-fill, minmax(180px,1fr)); */
    grid-auto-flow: dense;
    grid-gap: 20px;
    align-items: center;
  }
}

@media (max-width: 420px) {
  .clients_grid {
    grid-template-columns: repeat(auto-fill, minmax(110px, 1fr));
  }
}

.grid {
  padding: 1.4em;
  max-width: 1200px;
  display: grid;
  grid-gap: 1em;
  margin: 2rem auto;
}

.grid > div {
  padding: 1em;
  border: 1px solid #ccc;
  // box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1), 0 20px 20px rgba(0, 0, 0, 0.05);
  // box-shadow: 0 3px 5px -1px rgba(0, 0, 0, 0.2), 0 5px 8px rgba(0, 0, 0, 0.14), 0 1px 14px rgba(0, 0, 0, 0.12);
}

// .item-a {
// grid-column-start: 1;
// grid-column-end: 5;
// }
.item-b {
  background: url('https://images.unsplash.com/photo-1523529364348-e930dcb39642?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1500&q=80') 0 0 / cover no-repeat;
}

.item-f {
  background: url('https://images.unsplash.com/photo-1529604278261-8bfcdb00a7b9?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1502&q=80') center / cover no-repeat;
}

@media (min-width: 860px) {
  .grid {
    grid-template-columns: repeat(4, 1fr);
    grid-template-rows: repeat(10, auto);
  }

  .item-a {
    grid-column: 1 / 5;
    grid-row: 1 / 3;
  }

  .item-b {
    grid-column: 1 / 3;
    grid-row: 3 / 6;
  }

  .item-c {
    grid-column: 3 / 5;
    grid-row: 3 / 7;
  }

  .item-d {
    grid-column: 1 / 2;
    grid-row: 6 / 8;
  }

  .item-e {
    grid-column: 2 / 3;
    grid-row: 6 / 8;
  }

  .item-f {
    grid-column: 3 / 4;
    grid-row: 7 / 9;
  }

  .item-g {
    grid-column: 4 / 5;
    grid-row: 7 / 11;
  }

  .item-h {
    grid-column: 1 / 3;
    grid-row: 8 / 11;
  }

  .item-i {
    grid-column: 3 / 4;
    grid-row: 9 / 11;
  }
}
</style>
