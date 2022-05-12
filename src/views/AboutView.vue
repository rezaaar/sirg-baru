<template>
  <div class="about">
    <NavbarApp />
    <HeroApp />
    <AboutUs />
    <FooterApp />
  </div>
</template>

<script>
// @ is an alias to /src
import NavbarApp from '@/components/NavbarApp.vue'
import HeroApp from '@/components/HeroApp.vue'
import AboutUs from '@/components/AboutUs.vue'
import FooterApp from '@/components/FooterApp.vue'

export default {
  name: 'AboutView',
  components: {
    NavbarApp,
    HeroApp,
    AboutUs,
    FooterApp
  }
}
</script>