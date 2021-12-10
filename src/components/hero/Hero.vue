<template>
   <div class="container my-5 py-5 z-depth-1">


    <!--Section: Content-->
    <section class="px-md-5 mx-md-5 text-center dark-grey-text">
 
      <h3 class="font-weight-bold mb-5">Call to action</h3>

      <!--Grid row-->
      <div class="row">

      <FeatureCard />
      <FeatureCard />
      <FeatureCard />
      <FeatureCard />

      </div>


    </section>
    <!--Section: Content-->


  </div>
</template>

<script>
import FeatureCard from './FeatureCard.vue'

export default {
  name:'Hero',
  components: {
    FeatureCard
  }
  

}
</script>

<style>

</style>