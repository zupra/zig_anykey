<template lang="pug">
div

  .wrap
    //- .flex_wr.x_sb
    //-   h1.text_x5
    //-     //- span.BG
    //-     | ЕГАИС
    //-     br
    //-     | R-Keeper
    //-     br
    //-     | StoreHouse
    //-     br
    //-     | ККМ по 54-ФЗ

    //-   h2 Автоматизация
    h1.text_x4.bold_900.mb-2 Автоматизация ресторанов, баров и кафе
    .grid
      .item-a.white.bold.flex_col.x_sb.shadow
        //- .text_x4
        //-   span.BG Автоматизация ресторанов баров и кафе
        
        img.filter_1(
          src='https://static.tildacdn.com/tild3631-3632-4339-b131-663633663838/_.png'
        )
        .mt_auto.flex_wr.x_sb
          .BG.fr_1.m-1.p-1
            .text_x1.mb-1
              span(style="color: #37b44a;") _
              | CashDesk
            p Кассовый модуль с интуитивно понятным интерфейсом. Позволяет быстро и точно рассчитывать гостей и проводить кассовые операции

          .BG.fr_1.m-1.p-1
            .text_x1.mb-1
              span(style="color: #37b44a;") _ 
              | StoreHouse
            p Программа складского учета поможет полностью автоматизировать процесс управления производством в заведении

          .BG.fr_1.m-1.p-1
            .text_x1.mb-1
              span(style="color: #37b44a;") _ 
              | Manager
            p Mодуль позволяет совершать различные менеджерские операции, например разделить счёт или оставить комментарий к заказу для повара


        
      .item-b.white.bold.flex_col.x_sb
        
        .BG.p-1.mb-3.text_x1 Оборудование рабочиx мест кассиров и официантов
        .BG.p-1.text_s1 POS-системы для работы кассира, РOS-системы для работы официанта, Фискальный регистратор, Сервис-принтер, Денежный ящик

        //- , Manager, StoreHouse

        //- img(
        //-   style="width: 100%;"
        //-   :src="require(`@/static/fallout/fallout-robot.png`)"
        //- )
      .item-c.shadow
        //- h1.mb-3 item-c
        .center
          .bold_900.text_x5 На связи 24/7
          .text_x4 8(495)199-57-89
          //- .bold_900.mb-3 Ничто не должно остановить работу заведения
          .bold_900.text_x4
            a(
              href="https://chat.whatsapp.com/IjMFGwBS3ZnArTe7VqE6gm"
            ) WhatsApp
            | &emsp;
            a(
              href="https://t.me/joinchat/AGrzUxpLIxO-2vYeBcqxlA"
            ) Telegram

        
        .mt-3.bold Если у вас возникла срочная проблема
        .my-2 У нас всегда дежурят 2 IT-пециалиста. Вы можете вызвать техподдержку круглосутчно в любой день, включая праздники и выходные.
        .my-2 Техподдержка срочно воостановить работу заведения
        img(
          style="width: 100%;"
          src="https://images.unsplash.com/photo-1508766917616-d22f3f1eea14?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=600&q=80"
        )
      .item-d
        .bold_900.text_x3.mb-2 Установка оборудования
        ul
          li POS-система для работы кассира
          li POS-система для работы официанта
          li Фискальный регистратор
          li Сервис-принтер
          li Денежный ящик
        //- p Настройка удаленного рабочего места
        //- .my-3 Быстро и безопасно
        //- p В подвале телефон  - 8(495)199-57-89 и кнопка заказать звонок (клик - всплывающая форма телефон и имя и, наверное, необязательным полем с “краткая информация по вопросу”)
      
      .item-e
        h1.mb-3 item-e
        p.mb-3 _StoreHouse
        p Программа складского учета _StoreHouse поможет полностью автоматизировать процесс управления производством в заведении
      
      .item-f.white
        h1.mb-3 item-f
        p.mb-3 Digital audits, facilitated design thinking workshops, 
      
      .item-g
        h1.mb-3 item-g
        p.mb-3 Digital audits, facilitated design thinking workshops, digital strategy development, campaign and website 
        p.mb-3 Digital audits, facilitated design thinking workshops, digital strategy development, campaign and website analytics, user research, content strategy development, user scenarios and persona development and media strategy.
        h4 Blanditiis nisi commodi illo
      
      .item-h.shadow
          .bold_900.text_x3.mb-2 Установка оборудования и ПО*
          .flex
            div
              .bold оборудование
              p POS-система для работы кассира, РOS-система для работы официанта, Фискальный регистратор, Сервис-принтер, Денежный ящик
            p ПО: r_keeper_7_CashDesk, r_keeper_7_Manager, r_keeper_7_StoreHouse
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
.BG {
  background: rgba(#000, 0.8);
  line-height: 1;
  // padding: 0 0.3em;
}

.filter_1 {
  filter: drop-shadow(2px 4px 6px black);
}

.shadow {
  box-shadow: 0 1px 8px rgba(0, 0, 0, 0.25);
}

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
    grid-gap: 3em;
    align-items: center;
  }
}

@media (max-width: 420px) {
  .clients_grid {
    grid-gap: 1em;
    grid-template-columns: repeat(auto-fill, minmax(110px, 1fr));
  }
}

.wrap {
  max-width: 1200px;
  margin: 1rem auto;
  padding: 1.4em;
}

.grid {
  display: grid;
  grid-gap: 1em;
}

.grid > div {
  padding: 1em;
  border: 1px solid #ccc;
  height: 100%;
  // box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1), 0 20px 20px rgba(0, 0, 0, 0.05);
  // box-shadow: 0 3px 5px -1px rgba(0, 0, 0, 0.2), 0 5px 8px rgba(0, 0, 0, 0.14), 0 1px 14px rgba(0, 0, 0, 0.12);
}

.item-a {
  background: url('https://images.unsplash.com/photo-1554118811-1e0d58224f24?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1200&&q=80') center / cover no-repeat;
}

.item-b {
  background: url('https://images.unsplash.com/photo-1523529364348-e930dcb39642?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=600&q=80') 0 0 / cover no-repeat;
}

.item-f {
  background: url('https://images.unsplash.com/photo-1529604278261-8bfcdb00a7b9?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=300&q=80') center / cover no-repeat;
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
