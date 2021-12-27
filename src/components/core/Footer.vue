<template>
  <v-footer
    height="238"
    class="justify-center"
    color="#835D9D"
  >
    <social-media large />
  </v-footer>
</template>

<script>
  export default {
    name: 'CoreFooter',

    components: {
      SocialMedia: () => import('@/components/SocialMedia'),
    },
  }
</script>
