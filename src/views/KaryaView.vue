<template>
  <div class="karya">
    <NavbarApp />
    <KaryaLain/>
    <FooterApp />
  </div>
</template>

<script>
// @ is an alias to /src
import NavbarApp from '@/components/NavbarApp.vue'
import KaryaLain from '@/components/KaryaLain.vue'
import FooterApp from '@/components/FooterApp.vue'

export default {
    name: 'KaryaView',
    components: {
        NavbarApp,
        KaryaLain,
        FooterApp
  }
}
</script>

<style>

</style>