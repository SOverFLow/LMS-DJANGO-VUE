<template>
  
  <navbar/>
  <Hero/>
  <Service/>
  <Testimonial/>
  <Footer/>



</template>

<script>

import navbar from '@/components/navbar.vue';
import Hero  from '@/components/Hero.vue'
import Service from '@/components/Services.vue'
import Testimonial from '@/components/Testimonial.vue'
import Footer from '@/components/Footer.vue'

export default {
    name: 'HomeView',
    components: { navbar, Hero, Service, Testimonial, Footer }
}
</script>
