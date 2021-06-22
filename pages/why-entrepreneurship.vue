<template>
  <section class="page">
    <section class="section">
      <div class="row m-0 justify-content-between align-items-center">
        <div class="col-md-5 p-0">
          <img src="~/assets/img/jumbotron-img.jpg" class="section__img" alt="About LUE" />
        </div>
        <div class="col-md-6 p-0">
          <h2 class="section__heading">Why Entreprenuership</h2>
          <p class="section__paragraph px-0">
            Entrepreneurship isn't just about starting a business or leading an enterprise, we believe it is a skill-set and way of thinking that drives creativity and innovation. Its core is about building solutions to problems and taking the right steps to make them a reality.
            Entrepreneurs are not just business owners but passionate problem solvers.
          </p>
        </div>
      </div>
    </section>
    <section class="section section--bg">
      <div class="row m-0 justify-content-between align-items-center">
        <div class="col-md-6 p-0">
          <h2 class="section__heading">Our Impact</h2>
          <p class="section__paragraph px-0">
            We are building leaders across the continent and entrepreneurship is our tool.
            We are:
            <ul class="section__list">
              <li>Reaching out to young people to prepare them for the future.</li>
              <li>Creating an environment where innovation and creativity will thrive.</li>
              <li>Creating an ecosystem of linkages and partnerships relevant for sustainable economic development.</li>
              <li>We are joining the list of change-makers on the continent and beyond in creating a better Africa.</li>
            </ul>
          </p>
        </div>
        <div class="col-md-5 p-0">
          <img src="~/assets/img/school-boys.jpg" class="section__img" alt="About LUE" />
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
      title: `Why Entrepreneurship | Let's Use Entreprenuership`,
      meta: [
        {
          name: 'description',
          description: `Entrepreneurship isn't just about starting a business or leading an enterprise, we believe it is a skill-set and way of thinking that drives creativity and innovation.`
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
