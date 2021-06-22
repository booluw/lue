<template>
  <section class="page">
    <section class="section">
      <div class="row m-0 justify-content-between align-items-center">
        <div class="col-md-5 p-0">
          <img src="~/assets/img/street.jpg" class="section__img" alt="About LUE" />
        </div>
        <div class="col-md-6 p-0">
          <h2 class="section__heading">LUE Trade and Exhibitions</h2>
          <p class="section__paragraph px-0">
            Our nation and continent is blessed with many innovators and great business ideas but one thing had repeatedly stood as a major challenge, visiblity.
            Potentials that can pull global attention end up localized to our environments or in the trash because of the absence of relevant platforms that can reveal their potential.
            <br /><br />
            With this trade and exhibitions initiative, LUE will partner with relevant government bodies and industry experts to host trade exhibitions across the continent inviting innovators, businessmen and women, and investors
             from around the world to witness the creative market-viable ideas of the continent.
          </p>
        </div>
      </div>
    </section>
  </section>
</template>

<script>
export default {
  name: 'LueStreetPage',
  head() {
    return {
      title: `LUE Trade and Exhibitions | Let's Use Entreprenuership`,
      meta: [
        {
          name: 'description',
          description: `Our nation and continent is blessed with many innovators and great business ideas but one thing has repeatedly stood as a major challenge; Visibility.`
        },
        {
          name: 'keywords',
          description: 'LUE Trade, Street exhibitions, Street trading, Join LUE, Ideas Event'
        }
      ]
    }
  }
}
</script>
