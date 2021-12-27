<template>
  <section
    id="about"
    class="overflow-hidden my-10"
  >
    <v-row
      no-gutters
      class="d-flex justify-center"
    >
      <v-col
        cols="6"
        class="ma-12"
      >
        <v-img
          style="border-radius: 50px"
          :src="require('@/assets/video.gif')"
        />
      </v-col>
    </v-row>
  </section>
</template>

<script>
  export default {
    data: () => ({
      skills: [
        {
          name: 'Web Design',
          value: 100,
        },
        {
          name: 'Web Development',
          value: 75,
        },
        {
          name: 'Web Support',
          value: 90,
        },
      ],
    }),
  }
</script>
