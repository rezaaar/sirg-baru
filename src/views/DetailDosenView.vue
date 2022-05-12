<template>
  <div class="detaildosen">
    <NavbarApp />
    <DetailDosen />
    <FooterApp />
  </div>
</template>

<script>
// @ is an alias to /src
import NavbarApp from '@/components/NavbarApp.vue'
import DetailDosen from '@/components/DetailDosen.vue'
import FooterApp from '@/components/FooterApp.vue'

export default {
    name: 'DetailDosenView',
    components: {
        NavbarApp,
        DetailDosen,
        FooterApp
  }
}
</script>

<style>

</style>