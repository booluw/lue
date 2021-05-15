<template>
  <header class="header">
    <nuxt-link to="/">
      <img src="~/assets/img/lue-logo.png" alt="LUE logo transparent background" class="header__logo" />
    </nuxt-link>
    <nav class="header__nav">
      <input type="checkbox" id="menu" />
      <label for="menu" class="stairs"></label>
      <ul class="nav">
        <li>
          <nuxt-link to="/about" class="nav__link" exact-active-class="nav__link--active">
            About
            <i class="lni lni-chevron-right"></i>
          </nuxt-link>
        </li>
        <li>
          <nuxt-link to="/facilitators" class="nav__link" exact-active-class="nav__link--active">
            facilitators
            <i class="lni lni-chevron-right"></i>
          </nuxt-link>
        </li>
        <li>
          <nuxt-link to="/mentors" class="nav__link" exact-active-class="nav__link--active">
            mentors
            <i class="lni lni-chevron-right"></i>
          </nuxt-link>
        </li>
        <li>
          <nuxt-link to="/locations" class="nav__link" exact-active-class="nav__link--active">
            locations
            <i class="lni lni-chevron-right"></i>
          </nuxt-link>
        </li>
        <li class="mt-5 pt-5 mt-md-0 pt-md-0">
          <a href="#" @click.prevent="$emit('cta')" class="btn btn--link btn--cta">
            join us
          </a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'AppHeader'
}
</script>
