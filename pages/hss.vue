<template>
  <section class="page">
    <section class="section">
      <div class="row m-0 justify-content-between align-items-center">
        <div class="col-md-5 p-0">
          <img src="~/assets/img/mentors-img.jpg" class="section__img" alt="About LUE" />
        </div>
        <div class="col-md-6 p-0">
          <h2 class="section__heading">High School Spark</h2>
          <p class="section__paragraph px-0">
            The <b>High School Spark</b> Challenge is an Entreprenuershipeducation program and business idea competition for high schools in Nigeria.
            It is open to secondary schools and technical/vocational colleges across the country but this first edition is limited to schools in Niger State.
            <br /><br />
          </p>
          <a href="//apply.lueinitiative.org/hss" class="btn btn--link" target="_blank">Apply for HSS</a>
        </div>
      </div>
    </section>
  </section>
</template>

<script>
export default {
  name: 'FacilitatorsPage',
  head() {
    return {
      title: `High School Spark | Let's Use Entreprenuership`,
      meta: [
        {
          name: 'description',
          description: `These are teachers or tutors in various institutions and industries whose intrests align with the goals of LUE and want to join the network to influence the next generation of enterprenuers. They, teachers, are mentors and will be equipped with a flexible curriculum that will guide the mentorship process.`
        },
        {
          name: 'keywords',
          description: 'LUE Mentors, LUE in Schools, LUE School, Join LUE'
        }
      ]
    }
  }
}
</script>
