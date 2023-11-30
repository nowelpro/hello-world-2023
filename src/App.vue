<template>
  <div id="app">

  <b-navbar toggleable="sm" type="light" variant="light">

    <div class="container">

        <b-navbar-brand href="#">Магазин</b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <b-nav-item href="#">Ссылка</b-nav-item>
            <b-nav-item href="#" disabled>Отключено</b-nav-item>
          </b-navbar-nav>

        </b-collapse>

    </div>

  </b-navbar>

    <div class="container">
      <b-row>
        <b-col cols="2">меню</b-col>
        <b-col cols="10">
          <b-jumbotron header="BootstrapVue" lead="Компоненты Bootstrap v4 для Vue.js 2">
            <p>Для получения дополнительной информации посетите веб-сайт</p>
            <b-button variant="primary" href="#">Больше информации</b-button>
          </b-jumbotron>
          <hr>


        <b-card
          title="Заголовок карточки"
          img-src="https://picsum.photos/600/300/?image=25"
          img-alt="Изображение"
          img-top
          tag="article"
          style="max-width: 20rem;"
          class="mb-2"
        >
          <b-card-text>
            Небольшой пример текста, который будет построен на заголовке карты и составляет основную часть содержимого карты.
          </b-card-text>

          <b-button href="#" variant="primary">Иди куда-нибудь</b-button>
        </b-card>


        </b-col>
      </b-row>
    



    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
}
</script>

<style>
</style>
