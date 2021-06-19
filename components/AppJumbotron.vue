<template>
  <section class="jumbotron">
    <div class="row m-0 align-items-center justify-content-between">
      <div class="col-md-4 p-0">
        <h3 class="jumbotron__sub-heading">join the</h3>
        <h1 class="jumbotron__heading"><span>LUE</span> mentors</h1>
        <h3 class="jumbotron__sub-heading mt-md-3">program</h3>
      </div>
      <div class="col-md-6 p-0">
        <div class="jumbotron__text">
          <p class="my-3 pb-5">
            The need for mentors and educators is to help guide and support these proteges through the learning process and also
            come to their aid in times of LUE Initiative and you want to enroll as a mentor.
          </p>
          <button href="#" @click.prevent="$emit('cta')" class="btn btn--cta btn--link jumbotron__btn">
            become a mentor
          </button>
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
