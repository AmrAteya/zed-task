<template>
  <v-app>
    <core-view />
  </v-app>
</template>

<script>
  export default {
    name: 'App',
    components: {
      CoreView: () => import('@/components/core/View'),
    },
  }
</script>
