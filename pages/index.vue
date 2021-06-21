<template>
  <section class="page">
    <app-jumbotron @cta="modal = true"/>
    <section class="section pb-0">
      <div class="row m-0 justify-content-between align-items-center">
        <div class="col-md-5 p-0">
          <img src="~/assets/img/jumbotron-img.jpg" class="section__img" alt="About LUE" />
        </div>
        <div class="col-md-6 p-0">
          <h2 class="section__heading">About us</h2>
          <p class="section__paragraph col-md-9 p-0">
            <b>Let's Use Entrepreneurship</b> is one of the leading catalyst in driving economic and socio-economic gowth in Nigeria and Africa at large.
            We are geared towards raising exceptional enterprenuers and leaders who will solve real life problems and create value via Entrepreneurship.
          </p>
          <div class="mt-5">
            <nuxt-link to="/about-us" class="btn btn--link">The LUE Team</nuxt-link>
          </div>
        </div>
      </div>
    </section>
    <section class="section section--bg">
      <div class="row m-0 justify-content-between align-items-center">
        <div class="col-md-6 p-0">
          <h2 class="section__heading">mission</h2>
          <p class="section__paragraph col-md-9 p-0">
            To create an ecosystem where enterprenuers can thrive. We believe Entrepreneurship Education and it's
            practise holds a significant potential in the regards of driving Economic Development across the continent.
          </p>    
        </div>
        <div class="col-md-5 p-0">
          <img src="~/assets/img/jumbotron-img.jpg" class="section__img" alt="About LUE" />
        </div>
      </div>
    </section>
    <section class="section pb-0">
      <div class="row m-0 justify-content-between align-items-center">
        <div class="col-md-5 p-0">
          <img src="~/assets/img/jumbotron-img.jpg" class="section__img" alt="About LUE" />
        </div>
        <div class="col-md-6 p-0">
          <h2 class="section__heading">why Entrepreneurship</h2>
          <p class="section__paragraph">
            We believe Entrepreneurship isn't just about starting a business or leading an entreprise, we believe it is a skill-set and way of thinking
            that drives creativity and innovation. It's core is about building solutions to problems and taking the right steps to make them a reality.
            Entrepreneurs are not just business owners but passionate problem-solvers. Nations that promote entrepreneurial endeavors and provide a conductive environment for enterprenuers to thrive, will certainly be positioned for solutions and Economic Prosperity.
          </p>
        </div>
      </div>
    </section>
    <section class="section">
      <h2 class="section__heading">What we do</h2>
      <div class="row m-0 mt-5">
        <div class="col-md-3 p-0 pr-md-2">
          <div class="card">
            <h3 class="card__heading">LUE School</h3>
            <p class="card__text">
              To meet the rising rate of unemployment in Nigeria and across other African Economies.
              LUE initiative seeks by increasing the zest for entreprenuership.
            </p>
            <nuxt-link to="/lue-school" class="card__link">Read more about LUE School</nuxt-link>
          </div>
        </div>
        <div class="col-md-3 p-0 px-md-2">
          <div class="card">
            <h3 class="card__heading">LUE Focus</h3>
            <p class="card__text">
              This will serve as a platform for bright minds to meet, exchange ideas, and create relevant partnerships and collaborations for growth and success.
            </p>
            <nuxt-link to="/lue-focus" class="card__link">Read more about LUE Focus</nuxt-link>
          </div>
        </div>
        <div class="col-md-3 p-0 px-md-2">
          <div class="card">
            <h3 class="card__heading">LUE Street</h3>
            <p class="card__text">
              The street is filled with so much untapped potentials. Our street initiative taps into these intricate potentials and help refine them to meet global standards.
            </p>
            <nuxt-link to="/lue-street" class="card__link">Read more about LUE Street</nuxt-link>
          </div>
        </div>
        <div class="col-md-3 p-0 pl-md-2">
          <div class="card">
            <h3 class="card__heading">LUE Trade and Exhibitions</h3>
            <p class="card__text">
              Our nation and continent is blessed with many innovators and great business ideas but one thing has repeatedly stood as a major challenge; Visibility.
            </p>
            <nuxt-link to="/lue-trade" class="card__link">Read more about LUE Trade</nuxt-link>
          </div>
        </div>
      </div>
    </section>
    <app-modal v-if="modal == true" @close="modal = !modal" />
  </section>
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return {
      modal: false
    }
  },
  head() {
    return {
      title: `Home | Let's Use Entreprenuership`,
      meta: [
        {
          name: 'description',
          content: `Let's Use Entrepreneurship is one of the leading catalyst in driving economic and socio-economic gowth in Nigeria and Africa at large.
          We are geared towards raising exceptional enterprenuers and leaders who will solve real life problems and create value via Entrepreneurship.`
        },
        {
          name: 'keywords',
          content: 'LUE, Entreprenuership, High School Business, LUE Focus, David Utulor, Diatheke Empire, Africa Business'
        }
      ]
    }
  }
}
</script>
