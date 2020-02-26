<template>
  <div class="home">
    <HeaderShayna/>
    <HeroSection/>
    <WomenBanner/>
    <instaShayna/>
    <partnerLogo/>
    <footerShayna/>
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from '@/components/header-shayna.vue';
import HeroSection from '@/components/HeroSection.vue';
import WomenBanner from '@/components/WomenBanner.vue';
import instaShayna from '@/components/instaShayna.vue';
import partnerLogo from '@/components/partnerLogo.vue';
import footerShayna from '@/components/footerShayna.vue';

export default {
  name: 'Home',
  components: {
    HeaderShayna,
    HeroSection,
    WomenBanner,
    instaShayna,
    partnerLogo,
    footerShayna
  }
}
</script>
