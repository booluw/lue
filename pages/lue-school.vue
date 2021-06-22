<template>
  <section class="page">
    <section class="section">
      <div class="row m-0 justify-content-between align-items-center">
        <div class="col-md-5 p-0">
          <img src="~/assets/img/school-kids.jpg" class="section__img" alt="About LUE" />
        </div>
        <div class="col-md-6 p-0">
          <h2 class="section__heading">LUE School</h2>
          <p class="section__paragraph px-0">
            To meet the rising rate of unemployment across Africa, LUE School seeks to increase the zest for entreprenuership among young leaders.
            <br /><br />
            With a tight grip on the grassroots, LUE School targets both junior and hign school students in our pre-tertiary charter and higher education students in colleges or universities in the tertiary charter.
            <br /><br />
            For pre-tertiary institutions, LUE will leverage on the <em>'Clubs & Societies'</em> present and build a campus community network for tertiary institutions across the continent.
          </p>
        </div>
      </div>
    </section>
  </section>
</template>

<script>
export default {
  name: 'LueSchoolPage',
  head() {
    return {
      title: `LUE School | Let's Use Entreprenuership`,
      meta: [
        {
          name: 'description',
          description: `To meet the rising rate of unemployment across Africa, LUE School seeks to increase the zest for entreprenuership among young leaders.`
        },
        {
          name: 'keywords',
          description: 'LUE School, LUE in Schools, LUE School, Join LUE'
        }
      ]
    }
  }
}
</script>
