<template>
  <div>
    <!-- Hero section -->
    <div>
      <div class="d-none d-sm-flex" style="width: 100%">
        <Desktop style="width: 100%" />
      </div>
      <div class="d-flex d-sm-none">
        <Mobile />
      </div>
      <div></div>

      <!-- Why purchase -->
      <Why />
      <!-- Best -->
      <Best />
      <!-- Features -->
      <Features />
      <!-- Materials -->
      <br>
      <Materials />
      <br>
      <Testimonial />
    </div>

  </div>
</template>

<script>
import Desktop from "./Desktop/hero.desktop.vue";
import Mobile from "./Mobile/hero.mobile.vue";
import Why from "./why.home.vue";
import Best from "./best.home.vue"
import Features from './features.home.vue'
import Materials from './materials.home.vue'
import Testimonial from './testimonial.home.vue'
// import Tablet from './Tablet/hero.tablet.vue'
export default {
  components: {
    Desktop,
    Mobile,
    // Tablet
    Why,
    Best,
    Features,
    Materials,
    Testimonial
  },
};
</script>

<style>
</style>