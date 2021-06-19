<template>
  <section class="page">
    <app-jumbotron @cta="modal = true"/>
    <section class="section pb-0">
      <div class="col-md-6 p-0">
        <h2 class="section__heading">about us</h2>
        <p class="section__paragraph">
          <b>Let's Use Entrepreneurship</b> is one of the leading catalyst in driving economic and socio-economic gowth in Nigeria and Africa at large.
          We are geared towards raising exceptional enterprenuers and leaders who will solve real life problems and create value via Entrepreneurship.
        </p>
      </div>
    </section>
    <section class="section">
      <div class="col-md-6 p-0">
        <h2 class="section__heading">mission</h2>
        <p class="section__paragraph">
          To create an ecosystem where enterprenuers can thrive. We believe Entrepreneurship Education and it's
          practise holds a significant potential in the regards of driving Economic Development across the continent.
        </p>    
      </div>
    </section>
    <section class="section pb-0">
      <div class="col-md-6 p-0">
        <h2 class="section__heading">why Entrepreneurship</h2>
        <p class="section__paragraph">
          We believe Entrepreneurship isn't just about starting a business or leading an entreprise, we believe it is a skill-set and way of thinking
          that drives creativity and innovation. It's core is about building solutions to problems and taking the right steps to make them a reality.
          Entrepreneurs are not just business owners but passionate problem-solvers. Nations that promote entrepreneurial endeavors and provide a conductive environment for enterprenuers to thrive, will certainly be positioned for solutions and Economic Prosperity.
        </p>
        <br />
        <h3>Impact</h3>
        <p class="section__paragraph">
          We are building and helping individuals acress the continent and Entrepreneurship is our tool.
          <br />
          We are:
        </p>
        <ul class="section__list">
          <li>Reaching out to young people to prepare them for the future.</li>
          <li>Creating an environment where innovation and creativity will thrive.</li>
          <li>Creating an ecosystem of linkages and partnerships relevant for sustainable economic development.</li>
          <li>We are joining the list of change-makers on the continent and beyond in creating a better Africa.</li>
        </ul>
      </div>
    </section>
    <section class="section">
      <h2 class="section__heading">What we do</h2>
      <h3>LUE School</h3>
      <p class="section__paragraph col-md-6 px-0">
        To meet the rising rate of unemployment in Nigeria and across other African Economies.
        LUE initiative seeks by increasing the zest for entreprenuership.
        <br /><br />
        LUE School seeks to target young people, with the mind of grooming and conditionin them for the entrepreneurial path. With a tight grip on the grassroots, LUE school target both Junior and High school students in our pre-tertiary charter and Higher Education students in colleges and universities.
        With our expertly crafted curriculum and network of astute facilitators, these young ones will be positioned for life and impact.
        <br /><br />
        For pre-tertiary institutions, LUE will leverage on the 'Clubs & Societies' present and build a campus community network for tertiary institutions across the country and the continent. Following this route will be grant LUE access to an already active audience thereby aiding the effectiveness of the campaign.
      </p>
      <br /><br /><br />
      <h3>LUE Focus</h3>
      <p class="section__paragraph col-md-6 px-0">
        LUE Focus seeks to periodically convene and connect leaders, entrepreneurs, trailblazer, and world changers who have had exceptional track records
        in their respective disciplines and area of expertise to learn and share ideas and thoughts that would bring global impact and build a sustainable future for the African continent.
        <br /><br />
        This will serve as a platform for bright minds to meet, exchange ideas, and create relevant partnerships and collaborations for growth and success.
      </p>
      <br /><br /><br />
      <h3>LUE Street</h3>
      <p class="section__paragraph col-md-6 px-0">
        The street is filled with so much untapped potentials. Our street initiative taps into these intricate potentials and help refine them to meet global standards.
        <br /><br />
        Essentially, LUE Street seeks to target artisans and Small & Medium Scale Entreprises. These artisans and SME owners have inherent abilities and strong business acumen that has the potency of setting them on the global syage. Usually these set of persons lack the equired training, refinement and support to yield stndard results.
        <br /><br />
        Therefore, our objective here is to provide the necessary training and support for these persons. We will organize workshops to help groom and equip these artisans and business owners with the knowledge required for them to thrive in their respective fields of expertise. We will also provide funding for promising ventures who successfully undergo our programs.
      </p>
      <br /><br /><br />
      <h3>LUE Trade and Exhibitions</h3>
      <p class="section__paragraph col-md-6 px-0">
        Our nation and continent is blessed with many innovators and great business ideas but one thing has repeatedly stood as a major challenge; Visibility. Potential products that can pull global attention end up localized to our environments or in the trash because of absence of relevant platforms that can reveal their potentials.
        <br /><br />
        With this trade and exhibition initiative the LUE organisation will partner with relevant government bodies and industry experts to host trade exhibitions across the continent inviting innovators, businessmen and women, and investors from around the world to witness the creative market ideas of the continent.
      </p>
    </section>
    <section class="section section--bg">
      <div class="d-flex flex-column align-items-center justify-content-center">
        <h3 class="section__heading">We are looking for persons to help mentor the next generation of African enterprenuers</h3>
        <br />
        <a href="#" class="btn btn--link" @click.prevent="modal = true">Become a mentor</a>
      </div>
    </section>
    <app-modal v-if="modal == true" @close="modal = !modal" />
  </section>
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return {
      modal: false
    }
  },
  head() {
    return {
      title: `Home | Let's Use Entreprenuership`,
      meta: [
        {
          name: 'description',
          content: `Let's Use Entrepreneurship is one of the leading catalyst in driving economic and socio-economic gowth in Nigeria and Africa at large.
          We are geared towards raising exceptional enterprenuers and leaders who will solve real life problems and create value via Entrepreneurship.`
        },
        {
          name: 'keywords',
          content: 'LUE, Entreprenuership, High School Business, LUE Focus, David Utulor, Diatheke Empire, Africa Business'
        }
      ]
    }
  }
}
</script>
