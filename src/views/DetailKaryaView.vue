<template>
  <div class="detaildosen">
    <NavbarApp />
    <DetailKarya />
    <FooterApp />
  </div>
</template>

<script>
// @ is an alias to /src
import NavbarApp from '@/components/NavbarApp.vue'
import DetailKarya from '@/components/DetailKarya.vue'
import FooterApp from '@/components/FooterApp.vue'

export default {
    name: 'DetailKaryaView',
    components: {
        NavbarApp,
        DetailKarya,
        FooterApp
  }
}
</script>

<style>

</style>