<template>
  <header class="header">
    <nuxt-link to="/">
      <img src="~/assets/img/lue-logo.png" alt="LUE logo transparent background" class="header__logo" />
    </nuxt-link>
    <nav class="header__nav">
      <input type="checkbox" id="menu" ref="menu"/>
      <label for="menu" class="stairs"></label>
      <div class="nav">
        <ul class="nav__list mb-5 mb-md-0">
          <li>
            <nuxt-link to="/cohorts" class="nav__link" exact-active-class="nav__link--active">
              cohorts
              <i class="lni lni-chevron-right"></i>
            </nuxt-link>
          </li>
          <li>
            <nuxt-link to="/investors" class="nav__link" exact-active-class="nav__link--active">
              investors
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
            <nuxt-link to="/partners" class="nav__link" exact-active-class="nav__link--active">
              partners
              <i class="lni lni-chevron-right"></i>
            </nuxt-link>
          </li>
        </ul>
        <a href="#" @click.prevent="$emit('cta')" class="btn btn--link btn--cta mt-5 mt-md-0">
          Get in touch
        </a>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'AppHeader',
  watch: {
    '$route': 'handleToggle'
  },
  methods: {
    handleToggle() {
      this.$refs.menu.checked = false
    }
  }
}
</script>
