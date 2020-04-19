<template lang="pug">
#footer
  #F_grid
    form.fgItem(ref="ftr_form")
      input.mb-2(
        type="tel"
        placeholder="* Телефон"
      )
      textarea(placeholder="Сообщение")
      button(@click.prevent="submit()") Отправить

    .fgItem
      h4 Eсть вопросы или предложения?
      p Оставьте сообщение которое сразу придёт нам в SMS. Если это важно или интересно — мы оперативно ответим.
    
    .fgItem
      h4 Пообщаемся в СоцСетях?
      .Socials-icon.flex
        a(href="//vk.com/#")
          svg.icon
            use(xmlns:xlink='http://www.w3.org/1999/xlink', xlink:href='#icon_vk')
          //| vkontakte
        a(href="//facebook.com/#")
          svg.icon
            use(xmlns:xlink='http://www.w3.org/1999/xlink', xlink:href='#icon_fb')
          //| facebook
        a(href="//instagram.com/#")
          svg.icon
            use(xmlns:xlink='http://www.w3.org/1999/xlink', xlink:href='#icon_instagram')
          //| instagram


    .fgItem
      //- h4 OOO «
      //-   b ВИНСТОН
      //-   |»
      | г. Москва, Покровка 3/7
      br
      | тел.: +7(495) 64-255-64
      br
      | режим работы: Пн-Пт
      br
      | с 10-20 часов
      br
      | Сб-Вс - выходной
    .fgItem
      h4 Инфо
      nuxt-link(to="/#") О компании
      //-   a(href="/#") Обмен и возврат
      nuxt-link(to="/#") Отзывы
      nuxt-link(to="/contacts") Контакты
      nuxt-link(to="/cooperation") Сотрудничество
      //- a(href="#") Узнать статус заказа


    .fgItem.Socials-icon
      h4 Поделиться
      a(href="/#")
        svg.icon
          use(xmlns:xlink='http://www.w3.org/1999/xlink', xlink:href='#icon_twitter')
        | share twitter
      a(href="/#")
        svg.icon
          use(xmlns:xlink='http://www.w3.org/1999/xlink', xlink:href='#icon_vk')
        | share vkontakte
      a(href="/#")
        svg.icon
          use(xmlns:xlink='http://www.w3.org/1999/xlink', xlink:href='#icon_fb')
        | share facebook
      a(href="/#")
        svg.icon
          use(xmlns:xlink='http://www.w3.org/1999/xlink', xlink:href='#icon_googleplus')
        | share Gplus
      a(href="/#")
        svg.icon
          use(xmlns:xlink='http://www.w3.org/1999/xlink', xlink:href='#icon_ok')
        | share odnoklassniki

  <SocIcon/>
</template>

<script>
import SocIcon from '~/components/SocIcon.vue'
export default {
  components: {
    SocIcon
  },
  data() {
    return {}
  }
}
</script>

<style lang="stylus" scoped>
#footer {
  margin-top: 5em;
  // background-image: linear-gradient(135deg, #FD6585 10%, #0D25B9 100%);
  background: #444;
  padding: 3em 0;
  color: #EEE;

  h4 {
    color: #FFF;
    line-height: 1;
  }

  a {
    color: #cddc39;
    display: block;

    &:hover {
      color: #FFF;
    }
  }
}

#F_grid {
  max-width: 1080px;
  margin: auto;
  padding: 0 1em;

  @media screen and (min-width: 620px) {
    // background #000
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    grid-gap: 1rem;
  }
}

.fgItem {
  margin: 2em 1em;
}

.Socials-icon {
  a {
    white-space: nowrap;

    &:hover .icon {
      background: rgba(#000 0.45);
    }
  }

  .icon {
    border-radius: 3px;
    vertical-align: middle;
    width: 16px;
    height: 16px;
    padding: 10px;
    box-sizing: content-box;
    margin: 4px;
    fill: #FFF;
    background: rgba(#EEE 0.2); // $header
  }
}
</style>
