<template>
  <div class="home">
    <div>
      
    </div>
    
    <Carousel />
    <HelloWorld />
  </div>
</template>

<script>

import HelloWorld from '@/components/HelloWorld.vue'
import Carousel from '@/components/Carousel.vue'

export default {
  name: 'HomeView',
  components: {
    
    HelloWorld,
    Carousel
}
}
</script>
