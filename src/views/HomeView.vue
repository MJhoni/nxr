<template>
  <div class="home">
    <HeaderNxrmalE />
    <HeroSectionNxrmalE />
    <BannerNxrmalE />
    <InstaNxrmalE />
    <PartnerNxrmal />
    <FooterNxrmalE />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeaderNxrmalE from '@/components/HeaderNxrmalE.vue'
import HeroSectionNxrmalE from '@/components/HeroSectionNxrmalE.vue'
import BannerNxrmalE from '@/components/BannerNxrmalE.vue'
import InstaNxrmalE from '@/components/InstaNxrmalE.vue'
import PartnerNxrmal from '@/components/PartnerNxrmal.vue'
import FooterNxrmalE from '@/components/FooterNxrmalE.vue'


export default {
  name: 'HomeView',
  components: {
    HeaderNxrmalE,
    HeroSectionNxrmalE,
    BannerNxrmalE,
    InstaNxrmalE,
    PartnerNxrmal,
    FooterNxrmalE
  }
}
</script>
