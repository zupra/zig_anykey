<template lang="pug">

.wrap


  h1.mb-2.text_x4.bold_900 Автоматизация ресторанов, баров и кафе
  //- .mb-4.bold.text_x3
  //-   i.bold_900 24/7 
  //-   | 8(495)199-57-89
  //-   a.mx-1(
  //-     href="https://chat.whatsapp.com/IjMFGwBS3ZnArTe7VqE6gm"
  //-   ) WhatsApp
  //-   a(
  //-     href="https://t.me/joinchat/AGrzUxpLIxO-2vYeBcqxlA"
  //-   ) Telegram







  //- :options="options"
  agile.mb-3(
    :nav-buttons="false" :autoplay-speed="5000" :speed="2500" fade pause-on-hover pause-on-dots-hover autoplay
  )

    //- img.slide(src='https://images.unsplash.com/photo-1554118811-1e0d58224f24?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1200&h=400&q=80')
    img.slide(src='https://images.unsplash.com/photo-1526234362653-3b75a0c07438?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1200&h=400&q=70')
    img.slide(src='https://images.unsplash.com/photo-1525610553991-2bede1a236e2?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=min&w=1200&h=400&q=70')

    //- div(
    //-   v-for="i in 5" :key="i"
    //- ) 
    //-   h1 HELLO_{{i}}

  //- swiper
  //-   swiper-slide
  //-     h1 slide 1
  //-   swiper-slide
  //-     h1 slide 2


    //-
      .fr_1(
        style="white-space: nowrap"
      )
        .ml-5.center
          .bold_900.text_x2 24/7 Поддержка
          //- На связи 24/7
          .bold.text_x2 8(495)199-57-89
          .bold_900.text_x1
            a(
              href="https://chat.whatsapp.com/IjMFGwBS3ZnArTe7VqE6gm"
            ) WhatsApp
            | &emsp;
            a(
              href="https://t.me/joinchat/AGrzUxpLIxO-2vYeBcqxlA"
            ) Telegram
        
        //- .my-2 У нас всегда дежурят 2 IT-пециалиста.
  //- p ЕГАИС, R-Keeper, StoreHouse, ККМ по 54-ФЗ

  .grid
    .item-a.p-2.white.bold.flex_col.x_sb.shadow
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


      
    .item-b.p-3.white.bold.flex_col.x_sb
      
      .mb-5.text_x2 
        span.BG Оборудование рабочиx мест кассиров и официантов
      //- .BG.p-1.mt-5.text_s1 POS-системы для работы кассира, РOS-системы для работы официанта, Фискальный регистратор, Сервис-принтер, Денежный ящик
      .mt-5.text_x2
        span.BG Эффективная работа персонала
      //- блокирующие (кассовые) инциденты

    .item-c.p-3
      .mb-3 Учёт каждой единицы товара в магазине, дистанционный контроль продавцов и их показателей, учёт товара на складе и в сети торговых точек, анализ динамики закупок и продаж по товарам или услугам за любой период времени



      
      //-
        .mb-2 Техподдержка в течении 20 минут реагирует на проблемы.
        .flex.x_sb.bold_900.mb-3 
          | 8(495)199-57-89
          a.mx-1(
            href="https://chat.whatsapp.com/IjMFGwBS3ZnArTe7VqE6gm"
          ) WhatsApp
          a(
            href="https://t.me/joinchat/AGrzUxpLIxO-2vYeBcqxlA"
          ) Telegram

      //- .mt-3.bold Если у вас возникла срочная проблема
      //- .my-2 У нас всегда дежурят 2 IT-пециалиста. Вы можете вызвать техподдержку круглосутчно в любой день, включая праздники и выходные.
      //- .my-2 Техподдержка срочно воcстановить блокирующие (кассовые) инциденты
      img(
        src="https://images.unsplash.com/photo-1508766917616-d22f3f1eea14?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=500&q=70"
      )
    .item-d.text_s2
      h3.bold_900.text_x3.mb-2 Удаленная помощь
      p Даже если у вас не стоит программ удаленного доступа, мы можем помочь прямо сейчас!

      h3.bold_900.text_x2.my-2 Оборудование
      .bold Установка, продажа, ремонт
      //- .mb-3 Индивидуальный подбор оборудования под запросы и потребности.
      .mb-3 POS-оборудование, оргтехника, расходные материалы.

      //- ul.ml-1.text_x2
      //-   li POS-система для работы кассира
      //-   li POS-система для работы официанта
      //-   li Фискальный регистратор
      //-   li Сервис-принтер
      //-   li Денежный ящик

      //- .mb-2 C r_keeper ресторатору доступны все необходимые инструменты управления залом, складом и производством.
      //- .mb-2 Удобно считать и отслеживать складские остатки, взаимодействовать с поставщиками, получать комплексные отчеты и управлять бухгалтерским и налоговым учетом.
      // - p То же касается склада и кухни — вы всегда знаете, сколько продуктов должно быть на складе и сколько весит каждое блюдо
      //- p Настройка удаленного рабочего места
      //- .my-3 Быстро и безопасно
      //- p В подвале телефон  - 8(495)199-57-89 и кнопка заказать звонок (клик - всплывающая форма телефон и имя и, наверное, необязательным полем с “краткая информация по вопросу”)
    
    .item-e.text_s2
      h3.bold_900.text_x3.mb-2 StoreHouse
      //- .mb-2 Программа StoreHouse решает задачу по учёту складских остатков и контролю списания товаров. В Store House ведутся калькуляционные карты, а также технологические и технико-технологические карты, рассчитывается калорийность блюд.
      //- Программа StoreHouse позволяет осуществлять полный контроль расходования продуктов, эффективно управлять себестоимостью, правильно организовать закупки, контролировать действия персонала
      p R-Keeper передает информацию о продажах в StoreHouse, которая в свою очередь сводит воедино приход, расход, составляет технологические карты приготовления блюд, также производит расчет калькуляции каждого из них и расчет остатков на складе.
    .item-f.p-2.white
      .bold.mb-2 Облачные решения
      p Хранение и поддержка серверов rkeeper, iiko, storehouse, 1c.
      p Из любой точки земли можно зайти в систему и увидеть полную картину бизнеса. 
    
    .item-g
      h3.mb-3 Сертификаты
      p Получение, продление и поддержка любых электронных подписей, включая ЕГАИС и сертификаты для регистрации на сайте ФНС. Подготовка рабочего места для работы с сертификатом, регистрация на государственных порталах
    
    .item-h
        .bold_900.text_x1.mb-2 ЕГАИС, R-Keeper, StoreHouse, ККМ по 54-ФЗ
        .mb-2 Ресторатору доступны все необходимые инструменты управления залом, складом и производством.
        .mb-2 Удобно считать и отслеживать складские остатки, взаимодействовать с поставщиками, получать комплексные отчеты и управлять бухгалтерским и налоговым учетом.
        //- .flex
        //-   div
        //-     .bold оборудование
        //-     p POS-система для работы кассира, РOS-система для работы официанта, Фискальный регистратор, Сервис-принтер, Денежный ящик
        //-   p ПО: r_keeper_7_CashDesk, r_keeper_7_Manager, r_keeper_7_StoreHouse
    .item-i
      h3.mb-2 Организация удаленного доступа
      p.mb-3 Настройка удаленного рабочего места. Создание безопасных VPN туннелей для удаленной работы из любой точки




  //-
    h3.center.bold_900.text_x3.my-4 Установка, продажа и ремонт оборудования
    .Grid(style="--columns: 3;")
      .Grid_item.border_odd_y

        h3.mb-3.text_x1.mb_2 POS-системы
        p для работы официанта, для работы кассира
      .Grid_item.border_odd_y
        h3.mb-3.text_x1.mb_2 Фискальные регистраторы
        p Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis nisi commodi illo perspiciatis? Explicabo, corrupti.
      .Grid_item.border_odd_y
        h3.mb-3.text_x1.mb_2 Сервис-принтеры
        p Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis nisi commodi illo perspiciatis? Explicabo, corrupti.


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
    // Logo,
  },
  data() {
    return {
      options: {
        infinite: true,
        slidesToShow: 3,
        navButtons: false,
        dots: false
      }
    }
  }
}
</script>

<style lang="stylus">
// VueAgile styles
.agile {
  &__dots {
    bottom: 10px;
    // flex-direction: column;
    right: 30px;
    position: absolute;
  }

  &__dot {
    // margin: 5px 0;
    margin: 1em;

    button {
      background-color: transparent;
      border: 1px solid gold;
      cursor: pointer;
      display: block;
      font-size: 0;
      line-height: 0;
      // margin: 0;
      // padding: 0;
      transition-duration: 0.3s;
      width: 30px;
      height: 30px;
    }

    &--current, &:hover {
      button {
        background-color: gold;
      }
    }
  }
}

// Slides styles
.slide {
  display: block;
  height: 500px;
  object-fit: cover;
  width: 100%;
  background: #000;
}

// ==============
.BG {
  background: #000; // #012635; // #122a35; // rgba(#000, 0.8);
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
  max-width: 1600px;
  margin: 0 auto;

  &_grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
    /* grid-template-rows: repeat(auto-fill, minmax(180px,1fr)); */
    grid-auto-flow: dense;
    grid-gap: 1em; // 3em;
    align-items: center;
  }
}

@media (max-width: 420px) {
  .clients_grid {
    // grid-gap: 1em;
    grid-template-columns: repeat(auto-fill, minmax(110px, 1fr));
  }
}

// Установка оборудования
.Grid {
  --columns: auto-fit;
  display: grid;
  grid-template-columns: repeat(var(--columns), minmax(0, 1fr));

  &_item {
    padding: 0.5em 1em 1em;
  }
}

.border_odd_y {
  & + & {
    border-left: 1px solid #CCC;
  }
}

.wrap {
  max-width: 1280px;
  margin: 1rem auto;
  padding: 1em;
}

.grid {
  display: grid;
  grid-gap: 1em;
}

/*
.grid > div {
  padding: 1em;
  border: 1px solid #ccc;
  height: 100%;
  // box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1), 0 20px 20px rgba(0, 0, 0, 0.05);
  // box-shadow: 0 3px 5px -1px rgba(0, 0, 0, 0.2), 0 5px 8px rgba(0, 0, 0, 0.14), 0 1px 14px rgba(0, 0, 0, 0.12);
}
*/
.item-a {
  background: url('https://images.unsplash.com/photo-1554118811-1e0d58224f24?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1200&&q=70') center / cover no-repeat;
}

.item-b {
  background: url('https://images.unsplash.com/photo-1556742393-d75f468bfcb0?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=600&q=70') center / cover no-repeat;
}

.item-c {
  // background-color: #000;
  // background-image: radial-gradient(
  // at 300px 300px,
  // rgba(159, 0, 191, 0.9) 0,
  // #4d4fa7 70%
  // );
  background: #000; // linear-gradient(to bottom, #4d3e67, #8f76bc);
  color: #FFF;
}

.item-f {
  background-color: #000; // #8f76bc;
  // background: url('https://images.unsplash.com/photo-1529604278261-8bfcdb00a7b9?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=300&q=80') center / cover no-repeat;
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
