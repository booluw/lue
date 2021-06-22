<template>
  <section class="page">
    <section class="section">
      <div class="row m-0 justify-content-between align-items-center">
        <div class="col-md-5 p-0">
          <img src="~/assets/img/partners-img.jpg" class="section__img" alt="About LUE" />
        </div>
        <div class="col-md-6 p-0">
          <h2 class="section__heading">Partners</h2>
          <p class="section__paragraph px-0">
            As an organisation, we understand the gravity of the work we have at hand and recognize dukly the role of partnerships in helping us get the best results.
            We are open to partnerships and collaborations with individuals and organisations alike to help achieve our mission.
          </p>
          <p class="section__paragraph px-0 mt-3">
            <b>Want to be a partner?</b><br />
            Send a mail to <a href="mailto:fellowships@lueinitiative.org">fellowships@lueinitiative.org</a>.
          </p>
        </div>
      </div>
    </section>
  </section>
</template>

<script>
export default {
  name: 'PartnersPage',
  head() {
    return {
      title: `Partners | Let's Use Entreprenuership`,
      meta: [
        {
          name: 'description',
          description: `As an organisation, we understand the gravity of the work we have at hand and recognize dukly the role of partnerships in helping us get the best results. We are open to partnerships and collaborations with individuals and organisations alike to help achieve our mission.`
        },
        {
          name: 'keywords',
          description: 'LUE Mentors, LUE Partners, Join LUE'
        }
      ]
    }
  }
}
</script>
