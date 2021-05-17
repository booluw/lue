<template>
  <section class="jumbotron">
    <div class="row m-0 align-items-center justify-content-between">
      <div class="col-md-4 p-0">
        <h3 class="jumbotron__sub-heading">join the</h3>
        <h1 class="jumbotron__heading"><span>LUE</span> facilitators</h1>
        <h3 class="jumbotron__sub-heading mt-md-3">program</h3>
      </div>
      <div class="col-md-6 p-0">
        <div class="jumbotron__text">
          <p class="my-3 pb-5">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid, eaque dolores. Ullam quae quod, assumenda officiis nostrum qui eos eveniet velit mollitia, explicabo, facilis aliquid provident quaerat animi quo numquam?
          </p>
          <a href="#" @click.prevent="$emit('cta')" class="btn btn--cta btn--link jumbotron__btn">
            become a facilitator
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'AppJumbotron'
}
</script>
