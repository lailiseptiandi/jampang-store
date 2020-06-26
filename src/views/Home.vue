<template>
  <div class="home">
    <HeaderJampang />
    <HeroJampang />
    <WomanJampang />
    <InstaJampang />
    <PartnerJampang />
    <FooterJampang />
  </div>
  </template>

<script>
// @ is an alias to /src
import HeaderJampang from '@/components/HeaderJampang.vue';
import HeroJampang from '@/components/HeroJampang.vue';
import WomanJampang from '@/components/WomanJampang.vue';
import InstaJampang from '@/components/InstaJampang.vue';
import PartnerJampang from '@/components/PartnerJampang.vue';
import FooterJampang from '@/components/FooterJampang.vue';

export default {
  name: 'Home',
  components: {
    HeaderJampang,
    HeroJampang,
    WomanJampang,
    InstaJampang,
    PartnerJampang,
    FooterJampang
  }
};
</script>
