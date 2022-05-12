<template>
  <div class="daftardosen">
    <NavbarApp />
    <DaftarDosen />
    <FooterApp />
  </div>
</template>

<script>
// @ is an alias to /src
import NavbarApp from '@/components/NavbarApp.vue'
import DaftarDosen from '@/components/DaftarDosen.vue'
import FooterApp from '@/components/FooterApp.vue'

export default {
    name: 'DaftarDosenView',
    components: {
        NavbarApp,
        DaftarDosen,
        FooterApp
  }
}
</script>

<style>

</style>