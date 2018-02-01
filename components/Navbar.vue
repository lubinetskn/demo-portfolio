<template>
  <div class="container">
    <nav class="navbar" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <a class="navbar-item" href="http://rockndraw.ru/">Мои Друзья</a>

        <button class="button navbar-burger">
          <span></span>
          <span></span>
          <span></span>
        </button>
      </div>

      <div class="navbar-menu">
        <div class="navbar-end">
          <nuxt-link class="navbar-item" to="/">Главная</nuxt-link>
          <nuxt-link class="navbar-item" to="/about">Обо мне</nuxt-link>
          <nuxt-link class="navbar-item" to="/projects">Проекты</nuxt-link>
          <nuxt-link class="navbar-item" to="/contact">Контакты</nuxt-link>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  method:{}
}
</script>
