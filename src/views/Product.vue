<template>
  <div class="home">
    <HeaderShayna />
    <FooterShayna />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderShayna from '@/components/HeaderShayna.vue';
import FooterShayna from '@/components/FooterShayna.vue';

export default {
  name: 'Product',
  components: {
    HeaderShayna,
    FooterShayna,
  },
};
</script>
