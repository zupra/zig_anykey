<template lang="pug">
#footer
  #F_grid 

    form(ref="ftr_form")
      input.mb-2(
        type="tel"
        placeholder="* Телефон"
      )
      textarea(placeholder="Сообщение")
      button.btn(@click.prevent="") Отправить



    div
      h4.bold_900 На связи 24/7
      b.text_x3 8(495)199-57-89
      .my-3.text_x1.bold_900
        a(
          href="https://chat.whatsapp.com/IjMFGwBS3ZnArTe7VqE6gm"
        ) WhatsApp
      .text_x1.bold_900
        a(
          href="https://t.me/joinchat/AGrzUxpLIxO-2vYeBcqxlA"
        ) Telegram

      .mt-3 Круглосутчно дежурят 2 IT-специалиста. 
      p Быстрое реагирование в течении 20 минут.


    .Socials-icon
      h4 Поделиться
      div  
        a(href="/#")
          svg.icon
            use(xmlns:xlink='http://www.w3.org/1999/xlink', xlink:href='#icon_twitter')
          | twitter
      div  
        a(href="/#")
          svg.icon
            use(xmlns:xlink='http://www.w3.org/1999/xlink', xlink:href='#icon_vk')
          | vkontakte
      div  
        a(href="/#")
          svg.icon
            use(xmlns:xlink='http://www.w3.org/1999/xlink', xlink:href='#icon_fb')
          | facebook
      div  
        a(href="/#")
          svg.icon
            use(xmlns:xlink='http://www.w3.org/1999/xlink', xlink:href='#icon_googleplus')
          | Gplus
      div  
        a(href="/#")
          svg.icon
            use(xmlns:xlink='http://www.w3.org/1999/xlink', xlink:href='#icon_ok')
          | odnoklassniki

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

<style lang="stylus">
#footer {
  margin-top: 5em;
  // background-image: linear-gradient(135deg, #FD6585 10%, #0D25B9 100%);
  background: #333;
  padding: 3em 0;
  color: #CCC;

  // line-height: 1.6;
  h4 {
    color: #FFF;
    margin-bottom: 1em;
    // line-height: 1;
  }

  a {
    color: #FFF;
    text-decoration: underline solid #999;

    &:hover {
      // color: #FFF;
      text-decoration-color: ivory;
    }
  }
}

/*  */
#F_grid {
  max-width: 1080px;
  margin: auto;
  padding: 0 1em;
  display: grid;
  grid-gap: 3rem;

  @media screen and (min-width: 620px) {
    // grid-gap: 3rem;
    grid-template-columns: repeat(3, auto);
    // grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  }
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
