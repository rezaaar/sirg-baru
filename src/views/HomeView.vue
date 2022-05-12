<template>
  <div class="home">
    <NavbarApp />
    <HeroApp />
    <LandingPageKarya />
    <LandingPageRiset />
    <FooterApp />
  </div>
</template>

<script>
// @ is an alias to /src
import NavbarApp from '@/components/NavbarApp.vue'
import HeroApp from '@/components/HeroApp.vue'
import LandingPageKarya from '@/components/LandingPageKarya.vue'
import LandingPageRiset from '@/components/LandingPageRiset.vue'
import FooterApp from '@/components/FooterApp.vue'

export default {
  name: 'HomeView',
  components: {
    NavbarApp,
    HeroApp,
    LandingPageKarya,
    LandingPageRiset,
    FooterApp
  }
}
</script>
