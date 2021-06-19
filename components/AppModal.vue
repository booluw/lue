<template>
  <section class="modal-container">
    <div class="modal">
      <div class="modal__header">
        <div class="d-flex align-items-center">
          <a href="#" @click.prevent="$emit('close')" class="modal__icon modal__icon--close lni lni-chevron-left" title="Close modal"></a>
          <h1 class="modal__heading">Join LUE</h1>
        </div>
      </div>
      <div class="modal__content">
        We believe Entrepreneurship isn't just about starting a business or leading an entreprise, we believe it is a skill-set and way of thinking that drives creativity and innovation. It's core is about building solutions to problems and taking the right steps to make them a reality. Entrepreneurs are not just business owners but passionate problem-solvers.
        <ul class="modal__list">
          <li class="list">
            <h2 class="list__heading">Mentors</h2>
            <div class="list__text">
              These are teachers or tutors in various institutions and industries whose intrests align with the goals of LUE and want to join the network to influence the next generation of enterprenuers. They, teachers, are mentors and will be equipped with a flexible curriculum that will guide the mentorship process.
            </div>
            <a href="mailto:fellowships@lueinitiative.org" class="btn btn--link list__btn">Become a mentor</a>
          </li>
          <li class="list">
            <h2 class="list__heading">Partners</h2>
            <div class="list__text">
              As an organisation, we understand the gravity of the work we have at hand and recognize dukly the role of partnerships in helping us get the best results. We are open to partnerships and collaborations with individuals and organisations alike to help achieve our mission.
            </div>
            <a href="mailto:fellowships@lueinitiative.org" class="btn btn--link list__btn">Become a Partner</a>
          </li>
        </ul>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'AppModal'
}
</script>
