<template>
  <section class="page">
    <section class="section">
      <div class="row m-0 justify-content-between align-items-center">
        <div class="col-md-5 p-0">
          <img src="~/assets/img/mentors-img.jpg" class="section__img" alt="About LUE" />
        </div>
        <div class="col-md-6 p-0">
          <h2 class="section__heading">Mentors</h2>
          <p class="section__paragraph px-0">
            These are teachers or tutors in various institutions and industries whose intrests align with the goals of LUE and want to join the network to influence the next generation of enterprenuers. They, teachers, are mentors and will be equipped with a flexible curriculum that will guide the mentorship process.
            <br /><br />        
            The need for mentors and educators is to help guide and support these proteges through the learning process and also
            come to their aid in times of LUE Initiative and you want to enroll as a mentor.
          </p><br />
          <a href="//apply.lueinitiative.org" class="btn btn--link" target="_blank">Click to apply as a LUE Mentor</a>
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
      title: `Mentors | Let's Use Entreprenuership`,
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
