<template>
  <section>
    <app-header @cta="modal = true" />
    <Nuxt />
    <app-footer />
    <app-modal v-if="modal"  @close="modal = !modal" />
  </section>
</template>

<script>
export default {
  data() {
    return {
      modal: false
    }
  }
}
</script>
