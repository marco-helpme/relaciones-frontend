<template>
  <div id="ageCheckPopupDiv">
    <div id="ageCheckPopupInner">
      <!-- <h1>YOU GOTTA BE <span>19+</span> TO GET IN HERE...</h1> -->
      <div class="agecake">
        <img src="~assets/img/agecake_aa2067ca.png">
      </div>
      <span class="agecheck_byline">
      </span>
      <ul>
        <li>I am at least 19 years old and have reached the age of majority and legal consent in the jurisdication in which I live</li>
        <li>I am aware of the adult-oriented nature of the content provided on this website and I am not offended by this content</li>
        <li>I agree that the website is not responsible for any content posted by users of the website</li>
        <li>I will report to the <a href="mailto:team@megapersonals.eu">support team</a> any suspected unlawful activity posted by other users</li>
        <li>I have read and agree to the complete <a href="public/term-of-use/index.html">Terms of Use</a></li>
      </ul>
      <div class="centered">
        <a class="categoryLink" href="/login">
          <button id="ageagree" class="btn">
            I Agree
          </button>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'TermsUse'
}
</script>

<style scoped>

</style>
