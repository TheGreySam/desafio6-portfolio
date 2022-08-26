<template>
  <div class="home">
    <div>
      
    </div>
    El diseñador 3d Sebastián Gómez, nacido en Alemania y emigrado a Chile con 6 años, se intereso en la informática para ampliar sus perspectivas laborales... ya que el Cine no paga las cuentas
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
    Carousel,
    HelloWorld,
    Carousel
}
}
</script>
