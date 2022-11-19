<template>
  <div class="home">
    <HeaderShayna />
    <HeroShayna />
    <WomenBannerShayna />
    <InstaShayna />
    <PartnerShayna />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue';
import HeaderShayna from '@/components/HeaderShayna.vue';
import HeroShayna from '@/components/HeroShayna.vue';
import WomenBannerShayna from '@/components/WomenBannerShayna';
import InstaShayna from '@/components/InstaShayna';
import PartnerShayna from '@/components/PartnerShayna';
import FooterShayna from '@/components/FooterShayna';

export default {
  name: 'HomeView',
  components: {
    HeaderShayna,
    HeroShayna,
    PartnerShayna,
    InstaShayna,
    WomenBannerShayna,
    FooterShayna,
  },
};
</script>
