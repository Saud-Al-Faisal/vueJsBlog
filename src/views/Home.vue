<template>
  <div class="home">
    <Carousel />
  </div>
</template>

<script>
// @ is an alias to /src

import Carousel from '@/components/layouts/Carousel.vue'
export default {
  name: 'Home',
  components: { Carousel }
}
</script>
