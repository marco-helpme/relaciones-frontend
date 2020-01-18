<template>
  <footer>
    <nav>
      <ul class="pager myStyle">
        <li>
          <a id="homeclick" href="/home">Home</a>
        </li>

        <li>|</li>
        <li><a href="/public/contact_us">Contact Us</a></li>
        <li>|</li>
        <li><a href="/public/terms">Policies &amp; Terms</a></li>
      </ul>
      <p class="buglink">
        <a href="/public/report_bug">Report Bug</a>
      </p>
    </nav>

    <div id="copyrigh" class="copyright_class">
      <!-- contact us footer  -->
      Copyright ©2019 MegaPersonals.eu
      <div style="padding-top:10px">
        For support please email <a href="mailto:team@megapersonals.eu">team@megapersonals.eu</a>
      </div>
      <div style="padding:10px 30px 0px 30px">
        MegaPersonals.eu is owned by Sfanti Grup Solutions S.R.L., 1 Anastasie Simu, Bucharest, 010294, Romania
      </div>
    </div>

    <div class="clearfix">
      <input
        type="hidden"
        class="jsp-env"
        data-escortbabylon="escortbabylon.com"
        data-imagedomain1="img1.lodef.net/imgs"
        data-imagedomain2="img2.lodef.net/imgs"
        data-videodomain1="video1.lodef.net/video"
        data-videodomain2="video2.lodef.net/video"
        data-imagemiddle="80000000000000000000000000000000"
        data-imageupload="image-processor.apnot.com/process"
        data-imagepreview="image-processor.apnot.com/static"
        data-captchaapi="captcha.lodef.net/api/captcha"
        data-captchaurl="captcha.lodef.net/captchas"
        data-lcdomain="listcrawler.com"
        data-transactionnocontexttoken="NO_CONTEXT_TRANSACTION_TOKEN"
data-usertermsofageversion="2"
      >
    </div>

    <script src="~/assets/js/image_utils.js" type="text/javascript" />
    <script src="~/assets/js/video_utils.js" type="text/javascript" />
    <!-- Global site tag (gtag.js) - Google Analytics -->
    <script async="" src="https://www.googletagmanager.com/gtag/js?id=UA-113349993-1" />
    <script>
      window.dataLayer = window.dataLayer || [];
      function gtag(){dataLayer.push(arguments);}
      gtag('js', new Date());

      gtag('config', 'UA-113349993-1');
    </script>
  </footer>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style scoped>

</style>
