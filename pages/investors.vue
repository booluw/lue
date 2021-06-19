<template>
  <section class="page">
    <section class="section">
      <h1 class="heading heading--fancy">Investors</h1>
      <h2 class="section__heading">description</h2>
      <p class="section__paragraph col-md-8 px-0">
        LUE pulls together bright ideas and business and creates finance linkages for them with her investors forum. Investors can join the network to access the organisation's trained start-ups with market viable ideas seeking for Investments.<br />
        This forum is aimed at making financing easily accessible for start-ups.
      </p>
      <p class="section__paragraph col-md-8 px-0 mt-3">
        <b>Want to invest in LUE?</b><br />
        Send a mail to <a href="mailto:invest@lueinitiative.org">invest@lueinitiative.org</a>.
      </p>
    </section>
  </section>
</template>

<script>
export default {
  name: 'InvestorsPage',
  head() {
    return {
      title: `Investors | Let's Use Entreprenuership`,
      meta: [
        {
          name: 'description',
          description: `LUE pulls together bright ideas and business and creates finance linkages for them with her investors forum. Investors can join the network to access the organisation's trained start-ups with market viable ideas seeking for Investments.`
        },
        {
          name: 'keywords',
          description: 'LUE Investors, Join LUE, David Utulor, Diatheke Empire'
        }
      ]
    }
  }
}
</script>
