<template>
  <div id="app" class="site-wrapper">
    <header class="px-1-mb">
      <NabVar />
    </header>
    <div id="site-content">
      <router-view />
    </div>
    <footer>
      <Footer />
    </footer>
  </div>
</template>
<script>
// @ is an alias to /src
import NabVar from '@/components/layouts/Header.vue'
import Footer from '@/components/layouts/Footer.vue'

export default {
  name: 'Home',
  components: {
    NabVar,
    Footer
  }
}
</script>
<style scoped>
#app {
  position: relative;
  min-height: 100%;
}
#site-content {
  padding-bottom: 73px;
}
footer {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
}
.px-1-mb {
  margin-bottom: 1px;
}
</style>
