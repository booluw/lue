<template>
  <section class="page">
    <section class="section">
      <div class="row m-0 justify-content-between align-items-center">
        <div class="col-md-5 p-0">
          <img src="~/assets/img/street.jpg" class="section__img" alt="About LUE" />
        </div>
        <div class="col-md-6 p-0">
          <h2 class="section__heading">LUE Street</h2>
          <p class="section__paragraph px-0">
            The street is filled with so many untapped potentials. Our street initiative taps into these intricate potentials and helps refine them to meet global standards.
            <br /><br />
            Essentially, our target here is <b>Artisans and SME's</b>. These artisans and small-scale business owners have a strong business acumen that has the potential for global recognition. Usually, these sets of persons or local businesses lack the required training,
            refinement, and support to yield standard results.
            <br /><br />
            Therefore, our objective here is to provide the necessary training and support for these persons. We will organize workshops to help groom and equip them with relevant business skills. We will also provide funding linkages and support for promising ventures who successfully undergo our programs. 
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
      title: `LUE Street | Let's Use Entreprenuership`,
      meta: [
        {
          name: 'description',
          description: `The street is filled with so many untapped potentials. Our street initiative taps into these intricate potentials and helps refine them to meet global standards.`
        },
        {
          name: 'keywords',
          description: 'LUE Street, Street business, Street business support, Join LUE, Ideas Event'
        }
      ]
    }
  }
}
</script>
