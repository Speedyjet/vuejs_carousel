<template>
  <div>
    <carousel>
      <carousel-slide>
        <div style="postition: absolute; left: 0; right: 0; text-align: center; top: 50%; color: #FFF; font-size: 16px;">
          hello
        </div>
        <img src="http://lorempicsum.com/futurama/630/300/1" width="100%">
      </carousel-slide>
      <carousel-slide>
        <div style="postition: absolute; left: 0; right: 0; text-align: center; top: 50%; color: #FFF; font-size: 16px;">
        bye 
        </div>
        <img src="http://lorempicsum.com/futurama/630/300/1" width="100%">
      </carousel-slide>
    </carousel>
  </div>
</template>
<script>
import Todos from './components/Todos'
import Carousel from './components/Carousel/Carousel'
import CarouselSlide from './components/Carousel/CarouselSlide'

export default {
  name: 'app',
  components: {
    Todos,
    Carousel,
    CarouselSlide
  }
}
</script>
