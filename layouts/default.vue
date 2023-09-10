<template>
    <div>
      <HeaderWebVue />
      <Nuxt />
      <FooterWeb />
    </div>
</template>

<script>
  import HeaderWeb from '~/components/HeaderWeb.vue';
  import FooterWeb from '~/components/FooterWeb.vue';

  export default {
    name: 'default',
    components: {
      HeaderWeb,
      FooterWeb,
    }
  }
</script>