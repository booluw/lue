<template>
  <section class="page">
    <section class="section">
      <div class="row m-0 justify-content-between align-items-center">
        <div class="col-md-5 p-0">
          <img src="~/assets/img/conference.jpg" class="section__img" alt="About LUE" />
        </div>
        <div class="col-md-6 p-0">
          <h2 class="section__heading">LUE Focus</h2>
          <p class="section__paragraph px-0">
            LUE Focus event periodically convenes and connect leaders, who have amazingly blazed trails in their respective disciplines and area of expertise to both learn and share ideas
            and thoughts that would bring global impact and build a sustainable future for the African continent.
            <br /><br />
            This will serve as a platform for bright minds to meet, exchange ideas, and create relevant partnerships and collaborations for growth and success.
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
      title: `LUE Focus | Let's Use Entreprenuership`,
      meta: [
        {
          name: 'description',
          description: `LUE Focus event periodically convenes and connect leaders, who have amazingly blazed trails in their respective disciplines and area of expertise to both learn and share ideas`
        },
        {
          name: 'keywords',
          description: 'LUE Focus Event, LUE in Schools, LUE Focus, Join LUE, Ideas Event'
        }
      ]
    }
  }
}
</script>
