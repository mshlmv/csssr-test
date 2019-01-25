<template lang="pug">
  section.container
    header.site-header
      img(src="~assets/logo.png" alt="CSSSR" class="logo")
      img(src="~assets/secret.png" alt="секретно заполнено собственноручно" class="secret")
    h1.page-title
      img(src="~/assets/delo.png" alt="Дело")
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>

<style lang="scss">
.container {
  min-height: 100vh;
  background: url("~assets/main-bg.jpg");
  width: 1000px;
  margin: 0 auto;
  padding: 70px 120px 100px 110px;
  /* position: relative; */
}
.site-header {
  position: relative;
}
.logo {
  display: block;
}
.secret {
  display: block;
  position: absolute;
  right: -65px;
  top: -15px;
}
.page-title {
  text-align: center;
  margin: 40px 0 0;
}
</style>

