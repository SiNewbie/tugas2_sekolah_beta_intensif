<template>
  <div>
    <HeaderWeb />
    <Nuxt />
    <FooterWeb />
  </div>
</template>

<script>
  
import HeaderWeb from '~/components/HeaderWeb.vue';
import FooterWeb from '~/components/FooterWeb.vue';

  export default {
      name: 'Default',
      components: {
        HeaderWeb,
        FooterWeb,
      }
  }
</script>