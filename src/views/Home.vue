<template>
  <div class="home">
    <Header />
    <HeroShayna />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue';
import HeroShayna from '@/components/HeroShayna.vue';

export default {
  name: 'Home',
  components: {
    Header,
    HeroShayna
  },
};
</script>
