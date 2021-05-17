<template>
  <section class="page">
    <app-jumbotron @cta="modal = true"/>
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
