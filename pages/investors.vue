<template>
  <section class="page">
    <section class="section">
      <div class="row m-0 justify-content-between align-items-center">
        <div class="col-md-5 p-0">
          <img src="~/assets/img/invest-img.jpg" class="section__img" alt="About LUE" />
        </div>
        <div class="col-md-6 p-0">
          <h2 class="section__heading">Investing with LUE</h2>
          <p class="section__paragraph px-0">
            LUE pulls together bright ideas and business and creates finance linkages for them with her investors forum. Investors can join the network to access the organisation's trained start-ups with market viable ideas seeking for Investments.<br />
            This forum is aimed at making financing easily accessible for start-ups.
          </p>
          <p class="section__paragraph px-0 mt-3">
            <b>Want to invest in LUE?</b><br />
            Send a mail to <a href="mailto:invest@lueinitiative.org">invest@lueinitiative.org</a>.
          </p>
        </div>
      </div>
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
