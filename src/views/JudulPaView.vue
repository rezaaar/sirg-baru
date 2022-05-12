<template>
  <div class="judulpa">
    <NavbarApp />
    <HeroApp />
    <DetailJudulPa />
    <FooterApp />
  </div>
</template>

<script>
// @ is an alias to /src
import NavbarApp from '@/components/NavbarApp.vue'
import HeroApp from '@/components/HeroApp.vue'
import DetailJudulPa from '@/components/DetailJudulPa.vue'
import FooterApp from '@/components/FooterApp.vue'

export default {
    name: 'JudulPaView',
    components: {
        NavbarApp,
        HeroApp,
        DetailJudulPa,
        FooterApp
  }
}
</script>

<style>

</style>