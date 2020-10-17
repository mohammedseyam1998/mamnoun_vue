<template>
  <div class="home">
    <warning-header msg=" تسوق بثقة في ظل جائحة فايروس كورونا "/>
    <nav-bar/>
    <warning-header msg="احرص على الاطلاع على آخر العروض المميزة "/>
    <slider/>
    <shopping-now/>
    <girl-clothes/>
    <boy-clothes/>
    <services/>
    <subscribe/>
    <main-footer/>
  </div>
</template>

<script>

import warningHeader from '@/components/warningHeader.vue'
import navbar from '@/components/navbar.vue'
import slider from '@/components/slider.vue'
import shoppingNow from '@/components/shoppingNow.vue'
import girlClothes from '@/components/girlClothes.vue'
import boyClothes from '@/components/boyClothes.vue'
import services from '@/components/services.vue'
import subscribe from '@/components/subscribe.vue'
import footer from '@/components/footer.vue'

export default {
  name: 'Home',
  components: {
   "warning-header" :warningHeader,
   "nav-bar" :navbar,
   "slider" : slider,
   "shopping-now":shoppingNow,
   "girl-clothes":girlClothes,
   "boy-clothes":boyClothes,
   "services":services,
   "subscribe":subscribe,
   "main-footer":footer
  }
}
</script>
<style lang="scss" scoped>

</style>
