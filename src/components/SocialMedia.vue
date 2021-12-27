<template>
  <div>
    <div class="d-flex justify-center">
      <v-img
        src="@/assets/zid-logo.png"
        max-height="50"
        max-width="200"
      />
    </div>
    <div class="d-flex justify-center mt-5">
      <v-icon
        v-for="(item, i) in items.slice(0, large ? items.length : 3)"
        :key="i"
        class="ma-5"
        color="white"
        v-text="item.icon"
      />
    </div>
    <v-icon
      style="position: absolute; bottom: 20px; right: 53px"
      color="#FFD12F"
      x-large
    >
      mdi-chat
    </v-icon>
    <v-icon
      style="position: absolute; bottom: 20px; left: 53px"
      color="#FFD12F"
      x-large
    >
      mdi-arrow-up-circle
    </v-icon>
  </div>
</template>

<script>
  export default {
    props: {
      large: {
        type: Boolean,
        default: false,
      },
    },

    data () {
      return {
        items: [
          {
            name: 'Youtube',
            icon: 'mdi-youtube',
          },
          {
            name: 'Linkeding',
            icon: 'mdi-linkedin',
          },
          {
            name: 'Instagram',
            icon: 'mdi-instagram',
          },
          {
            name: 'Twitter',
            icon: 'mdi-twitter',
          },
        ],
        iconforsupport: 'mdi-chat-outline',
      }
    },
  }
</script>
