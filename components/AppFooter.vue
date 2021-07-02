<template>
  <footer class="footer">
    <img src="~/assets/img/lue-logo.png" class="footer__img" alt="LUE logo" />
    <div class="row m-0 justify-content-between align-items-end">
      <div class="col-md-4 p-0">
        <p class="footer__paragraph">
          Our society comprises of people with different roles that couple to form the overall framework for the smooth running and sustenance
           of the initiative.
           <br /><br />
           <ul class="footer__links">
             <li>
               <nuxt-link to="/cohorts" class="footer__link">Cohorts</nuxt-link>
             </li>
             <li>
               <nuxt-link to="/investors" class="footer__link">Investors</nuxt-link>
             </li>
             <li>
               <nuxt-link to="/mentors" class="footer__link">Mentors</nuxt-link>
             </li>
             <li>
               <nuxt-link to="/partners" class="footer__link">Partners</nuxt-link>
             </li>
           </ul>
        </p>
      </div>
      <div class="col-md-4 mt-5 mt-md-0 p-0 footer__icon">
        <a href="//facebook.com/LUEinitiative" target="_blank">
          <i class="lni lni-facebook-original"></i>
        </a>
      </div>
    </div>
    <div class="footer__copy">
      &copy; 2021, LUE Initiative
    </div>
  </footer>
</template>

<script>
export default {
  name: 'AppFooter'
}
</script>
