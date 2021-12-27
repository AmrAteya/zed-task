<template>
  <v-app-bar
    class="app-bar"
    color="white"
    flat
  >
    <v-slide-x-transition>
      <v-img
        src="@/assets/zid-logo.png"
        class="shrink"
        contain
        height="100"
      />
    </v-slide-x-transition>
    <div class="center">
      <v-btn
        text
        class="ma-5"
      >
        الرئيسيه
      </v-btn>
      <v-btn
        text
        class="ma-5"
      >
        التصنيفات
      </v-btn>
      <v-btn
        text
        class="ma-5"
      >
        التطبيقات
      </v-btn>
      <v-btn
        text
        class="ma-5"
      >
        طور التطبيقات
      </v-btn>
    </div>
  </v-app-bar>
</template>

<script>
  export default {
    name: 'CoreAppBar',
  }
</script>
<style scoped>
.app-bar {
  position: absolute;
  margin-right: 199.83px;
  z-index: 10;
  left: 449.52px;
  right: 199.83px;
  top: 0px;
  display: inline-block;
  height: 10vh;
}
</style>
