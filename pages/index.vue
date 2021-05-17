<template>
  <section class="page">
    <app-jumbotron @cta="modal = true"/>
    <section class="section">
      <div class="row m-0">
        <div class="col-md-4">
          <div class="card">
            <i class="card__icon lni lni-map"></i>
            <h3 class="card__heading">Explore</h3>
            <p class="card__text">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit, expedita. Sequi sint totam et culpa modi quibusdam facilis! Earum, quas porro. Ea quaerat facilis deserunt.
            </p>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <i class="card__icon lni lni-ux"></i>
            <h3 class="card__heading">Network</h3>
            <p class="card__text">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit, expedita. Sequi sint totam et culpa modi quibusdam facilis! Earum, quas porro. Ea quaerat facilis deserunt.
            </p>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <i class="card__icon lni lni-bar-chart"></i>
            <h3 class="card__heading">Thrive</h3>
            <p class="card__text">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit, expedita. Sequi sint totam et culpa modi quibusdam facilis! Earum, quas porro. Ea quaerat facilis deserunt.
            </p>
          </div>
        </div>
      </div>
    </section>
    <app-modal v-if="modal == true" />
  </section>
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return {
      modal: false
    }
  }
}
</script>
