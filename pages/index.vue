<template lang="pug">
div

  .grid
    .item-a.mb-3
      h1.text_x3 Anykey.eXpert
      .text_x6.vintage ЕГАИС
        br
        | R-Keeper
        br
        | StoreHouse
        br
        | ККМ по 54-ФЗ
    .item-b
      h1.mb-3 item-b
      img(
        :src="require(`@/static/fallout/сash_register.png`)"
      )
      p.mb-3 Digital audits, facilitated design thinking workshops, digital strategy development, campaign and website analytics, user research, content strategy development, user scenarios and persona development and media strategy.
      //- img(
      //-   style="width: 100%;"
      //-   :src="require(`@/static/fallout/fallout-robot.png`)"
      //- )
    .item-c.mb-3
      h1.mb-3 item-c
      p.mb-3 Blanditiis nisi commodi illo minima quidem, molestias facere assumenda tenetur laborum fugit iure eos sint debitis error sit praesentium perspiciatis? Explicabo, corrupti.
      p Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis nisi commodi illo perspiciatis? Explicabo, corrupti.
      p.mb-3 Blanditiis nisi commodi illo minima quidem, molestias facere assumenda tenetur laborum fugit iure eos sint debitis error sit praesentium perspiciatis? Explicabo, corrupti.
      p Lorem ipsum dolor sit amet consectetur adipisicing elit. Blanditiis nisi commodi illo perspiciatis? Explicabo, corrupti.
      //- img(
      //-   style="width: 100%;"
      //-   :src="require(`@/static/fallout/fallout-syringe.png`)"
      //- )
      h2.center.my-2 Автоматизация
      img(
        style="width: 100%;"
        :src="require(`@/static/fallout/fallout-robot.png`)"
      )
    .item-d
      h1.mb-3 item-d
      p.mb-3 Digital audits, facilitated design thinking workshops, digital strategy development, campaign and website analytics, user research, content strategy development, user scenarios and persona development and media strategy.
    .item-e
      h1.mb-3 item-e
      p.mb-3 Digital audits, facilitated design thinking workshops, digital strategy development, campaign and website analytics, user research, content strategy development, user scenarios and persona development and media strategy.
    .item-f
      h1.mb-3 item-f
      p.mb-3 Digital audits, facilitated design thinking workshops, 
    .item-g
      h1.mb-3 item-g
      p.mb-3 Digital audits, facilitated design thinking workshops, digital strategy development, campaign and website 
      p.mb-3 Digital audits, facilitated design thinking workshops, digital strategy development, campaign and website analytics, user research, content strategy development, user scenarios and persona development and media strategy.
      h4 Blanditiis nisi commodi illo
    .item-h
      h1.mb-3 item-h
      p.mb-3 Digital audits, facilitated design thinking workshops, digital strategy development, campaign and website analytics, user research
      h4 Blanditiis nisi commodi illo
      h3 facilitated design thinking workshops, digital strategy development
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
.vintage {
  padding: 1rem;
  font-family: 'Exo 2', sans-serif;
  line-height: 1;
  /* transform: rotate(-10deg); */
  transform: skewY(-6deg);
  /* text-shadow: .1em .1em 0px #f0e8db, 8px 8px 0px #6c5257; */
  text-shadow: 0.1em 0.1em 0 rgba(47, 22, 80, 0.6);
  /* color: #962f42; */
  color: #f3efe9;
  text-align: right;
  background: url('https://www.pinclipart.com/picdir/big/202-2027371_charisma-fallout-4-vault-boy-a5-notebook-clipart.png') 0 0 / contain no-repeat, linear-gradient(rgba(255, 130, 0, 0.2), rgba(47, 22, 96, 0.04)), linear-gradient(rgba(255, 224, 180, 0.37), rgba(255, 224, 180, 0.37));
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

    img {
      width: 100%;
    }
  }
}

/* .clients-grid_item {
} */
.grid {
  padding: 1.4em;
  max-width: 1200px;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  margin: 50px auto;
}

.grid > div {
  padding: 1em;
}

.item-a {
  grid-column-start: 1;
  grid-column-end: 5;
}

.item-b {
  grid-column-start: 1;
  grid-column-end: span 4;
  border-top: 1px solid #ccc;
  border-left: 1px solid #ccc;
  border-right: 1px solid #ccc;
}

.item-c {
  grid-column-start: 1;
  grid-column-end: span 4;
  border: 1px solid #ccc;
}

.item-d {
  grid-column-start: 1;
  grid-column-end: span 4;
  border-left: 1px solid #ccc;
  border-bottom: 1px solid #ccc;
  border-right: 1px solid #ccc;
}

.item-e {
  grid-column-start: 1;
  grid-column-end: span 4;
  border-bottom: 1px solid #ccc;
  border-right: 1px solid #ccc;
  border-left: 1px solid #ccc;
}

.item-f {
  grid-column-start: 1;
  grid-column-end: span 4;
  border-left: 1px solid #ccc;
  border-right: 1px solid #ccc;
  border-bottom: 1px solid #ccc;
}

.item-g {
  grid-column-start: 1;
  grid-column-end: span 4;
  border-left: 1px solid #ccc;
  border-right: 1px solid #ccc;
  border-bottom: 1px solid #ccc;
}

.item-h {
  grid-column-start: 1;
  grid-column-end: span 4;
  border-left: 1px solid #ccc;
  border-right: 1px solid #ccc;
}

.item-i {
  grid-column-start: 1;
  grid-column-end: span 4;
  border-left: 1px solid #ccc;
  border-top: 1px solid #ccc;
  border-bottom: 1px solid #ccc;
  border-right: 1px solid #ccc;
}

@media (min-width: 860px) {
  .item-a {
    grid-column-start: 1;
    grid-column-end: 5;
    grid-row-start: 1;
    grid-row-end: 3;
  }

  .item-b {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 3;
    grid-row-end: 6;
    border-top: 1px solid #ccc;
    border-left: 1px solid #ccc;
    border-bottom: 1px solid #ccc;
    border-right: none;
  }

  .item-c {
    grid-column-start: 3;
    grid-column-end: 5;
    grid-row-start: 3;
    grid-row-end: 7;
    border: 1px solid #ccc;
  }

  .item-d {
    grid-column-start: 1;
    grid-column-end: 2;
    grid-row-start: 6;
    grid-row-end: 8;
    border-left: 1px solid #ccc;
    border-bottom: 1px solid #ccc;
    border-right: 1px solid #ccc;
  }

  .item-e {
    grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 6;
    grid-row-end: 8;
    border-left: none;
    border-right: none;
    border-bottom: 1px solid #ccc;
  }

  .item-f {
    grid-column-start: 3;
    grid-column-end: 4;
    grid-row-start: 7;
    grid-row-end: 9;
    border-left: 1px solid #ccc;
    border-bottom: none;
    border-right: none;
  }

  .item-g {
    grid-column-start: 4;
    grid-column-end: 5;
    grid-row-start: 7;
    grid-row-end: 11;
    border-left: 1px solid #ccc;
    border-right: 1px solid #ccc;
    border-bottom: 1px solid #ccc;
  }

  .item-h {
    grid-column-start: 1;
    grid-column-end: 3;
    grid-row-start: 8;
    grid-row-end: 11;
    border-left: 1px solid #ccc;
    border-bottom: 1px solid #ccc;
    border-right: none;
  }

  .item-i {
    grid-column-start: 3;
    grid-column-end: 4;
    grid-row-start: 9;
    grid-row-end: 11;
    border-left: 1px solid #ccc;
    border-top: 1px solid #ccc;
    border-bottom: 1px solid #ccc;
    border-right: none;
  }
}
</style>
