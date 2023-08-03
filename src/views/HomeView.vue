<template>
  <div class="home">
    <heroCompo class="con"></heroCompo>
    <aboutmeCompo class="con"></aboutmeCompo>
    <servicesCompo class="con"></servicesCompo>
    <testimonialsCompo class="con"></testimonialsCompo>
    <partnersCompo class="con"></partnersCompo>
    <contactCompo class="con"></contactCompo>

    <footerCompo class="con"></footerCompo>
  </div>
</template>

<script>
// @ is an alias to /src
import heroCompo from '@/components/heroCompo.vue';
import aboutmeCompo from '@/components/aboutmeCompo.vue';
import servicesCompo from "@/components/servicesCompo.vue";
import partnersCompo from '@/components/partnersCompo.vue';
import testimonialsCompo from '@/components/testimonialsCompo.vue';
import contactCompo from '@/components/contactCompo.vue';
import footerCompo from '@/components/footerCompo.vue';


export default {
  name: 'HomeView',
  components: {
    heroCompo,
    aboutmeCompo,
    servicesCompo,
    partnersCompo,
    testimonialsCompo,
    contactCompo,
    footerCompo
  }
}
</script>

<style scoped>
  .home{
    background-color: #2b2b2b;
  }

  .con{
    margin: 5px auto;
  }
</style>
