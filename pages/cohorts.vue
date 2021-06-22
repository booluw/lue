<template>
  <section class="page">
    <section class="section">
      <div class="row m-0 justify-content-between align-items-center">
        <div class="col-md-5 p-0">
          <img src="~/assets/img/peers.jpg" class="section__img" alt="About LUE" />
        </div>
        <div class="col-md-6 p-0">
          <h2 class="section__heading">Cohorts</h2>
          <p class="section__paragraph px-0">
            There is usually a bridge between idea and ventures, and to bridge this gap for intending Entrepreneurs, LUE organizes bootcamps that selects and accommodates a cohort of persons that will be immersed in intensive entrepreneurial training to help
            turn their ideas into viable ventures. <br /><br />
            The training will be in phases and successfully trained cohorts will have access to a lot of benefits like funding, mentorship, and the privilege of absorption into the LUE Networl of mentors and educators.
          </p>
          <p class="section__paragraph px-0">
            Application will be open soon for the next batch of cohorts.
          </p>
        </div>
      </div>
    </section>
  </section>
</template>

<script>
export default {
  name: 'CohortsPage',
  head() {
    return {
      title: `Cohorts | Let's Use Entreprenuership`,
      meta: [
        {
          name: 'description',
          description: `There is usually a bridge between idea and ventures, and to bridge this gap for intending Entrepreneurs, LUE organizes bootcamps that selects and accommodates a cohort of persons that will be immersed in intensive entrepreneurial training to help turn their ideas into viable ventures.`
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
