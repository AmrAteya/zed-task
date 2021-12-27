<template>
  <div>
    <!-- App bar -->
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
      <div>
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
    <!-- /App bar -->
    <!-- Welcome screen -->
    <section
      id="welcome"
    >
      <v-row class="d-flex justify-center mx-10 mt-10">
        <h1
          style="color: #8D5DA7; font-size: 36px; font-weight: 700; font-family: Cairo"
        >
          طور متجرك ووسع آفاق تجارتك مع سوق تطبيقات زد
        </h1>
      </v-row>
      <v-row class="d-flex justify-center mx-10 my-2">
        <v-col cols="4">
          <p style="font-family: 'Cairo'; font-size: 18px; font-weight: 100; text-align: center">
            طور تجارتك من خلال تطبيقات وحلول سوق تطبيقات زد التي تساعدك في نمو أرباحك عبر إدارة عمليات متجرك بشكل فعال واحترافي
          </p>
        </v-col>
      </v-row>
      <v-row
        class="d-flex justify-center mx-10 mb-10"
      >
        <v-btn
          color="#8D5DA7"
          x-large
          style="border-radius: 10px; align: center; height:60px; width: 295px"
        >
          <h3 style="color: #FDB515;">
            تصفح التطبيقات
          </h3>
          <v-icon
            color="#FDB515"
            large
          >
            mdi-chevron-left
          </v-icon>
        </v-btn>
      </v-row>
    </section>
    <!-- About -->
    <section
      id="about"
    >
      <div
        class="d-flex justify-center"
      >
        <v-img
          src="@/assets/Ellipse 250.png"
          max-width="250px"
          max-height="250px"
          style="z-index: 1; position: relative; bottom:-350px; right: 190px"
        />
        <v-img
          style="border-radius: 50px; z-index: 3; position: relative; top: -50px"
          max-width="45vw"
          height="60vh"
          src="@/assets/video.gif"
        />
        <v-img
          src="@/assets/Dot Pattern 3.png"
          max-width="164px"
          max-height="164px"
          style="z-index: 1; position: relative; top:-90px; right: -90px"
        />
      </div>
    </section>
    <!-- /about -->
    <!-- Features -->
    <section id="features">
      <div
        class="d-flex justify-start mr-10"
      >
        <h1 style="position: absolute; top: 1262.92px; font-size: 24px; color: #8D5DA7; font-weight: 700">
          كل ما تحتاجه لنمو متجرك في مكان واحد
        </h1>
        <h2 style="position: absolute; top: 1321.91px; max-width: 542.55px; font-size: 16px; font-weight: 100 ">
          مميزات سوق تطبيقات زد تساعدك في سهولة وسرعة الاستفاده من خدمات وحلول سوق التطبيقات لنمو متجرك ومضعفة أرباحك
        </h2>
        <div
          style="position: absolute; top: 1399.08px; height: 51px"
        >
          <div
            style="border-radius: 50%; background-color: white; width: 50px; height: 50px;display: block"
          >
            <v-img
              width="25px"
              height="20px"
              style="position: relative; top:14px; right: 12px"
              src="@/assets/icon1.svg"
            />
          </div>
          <div style="position: absolute; top: 13px; right: 70px; width: 800px; font-weight: 600; font-size: 14px; line-height: 24px">
            سهولة إدارة وتفعيل تطبيقاتك من نفس لوحة تحكم متجرك
          </div>
        </div>
        <div style="position: absolute; top: 1470.38px; height: 51px">
          <div
            style="border-radius: 50%; background-color: white; width: 50px; height: 50px;display: block"
          >
            <v-img
              width="25px"
              height="20px"
              style="position: relative; top:14px; right: 12px"
              src="@/assets/icon2.svg"
            />
          </div>
          <div style="position: absolute; top: 13px; right: 70px; width: 800px; font-weight: 600; font-size: 14px; line-height: 24px">
            دعم فني وتقني متكامل متوفر علي مدار الساعة
          </div>
        </div>
        <div style="position: absolute; top: 1541.99px; height: 51px">
          <div
            style="border-radius: 50%; background-color: white; width: 50px; height: 50px;display: block"
          >
            <v-img
              width="25px"
              height="20px"
              style="position: relative; top:14px; right: 12px"
              src="@/assets/icon3.svg"
            />
          </div>
          <div style="position: absolute; top: 13px; right: 70px; width: 800px; font-weight: 600; font-size: 14px; line-height: 24px">
            أسعار تنافسيه مع تجربه مجانية وباقات اشتراك متنوعة
          </div>
        </div>
        <v-btn
          style="position: absolute; top: 1633.99px; border-radius: 10px; align: center; height:60px; width: 295px"
          color="#8D5DA7"
        >
          <h3 style="color: #FDB515; font-weight: 700">
            تصفح التطبيقات
            <v-icon x-large>
              mdi-chevron-left
            </v-icon>
          </h3>
        </v-btn>
      </div>
      <div
        class="d-flex justify-end"
      >
        <v-img
          src="@/assets/Ellipse 250.png"
          max-width="367.32px"
          max-height="367.32px"
          style="z-index: 1; position: relative; bottom:-260px; right: 350px"
        />
        <v-img
          style="position: relative; top: 70px; right: 50px; border-radius: 40px; z-index: 2"
          src="@/assets/features.gif"
          max-width="700.98px"
          height="441px"
        />
        <v-img
          src="@/assets/Dot Pattern 3.png"
          max-width="176px"
          max-height="191px"
          style="z-index: 1; position: relative; top:25px; right: -40px"
        />
      </div>
    </section>
    <!-- /Features -->
    <!-- Highlights -->
    <section id="highlights">
      <div
        class="d-flex justify-center"
      >
        <h1 style="max-width: 542.55px; font-size: 24px; font-weight: 600 ">
          التطبيقات المميزه
        </h1>
      </div>
      <div
        class="d-flex justify-center"
      >
        <h1 style=" font-size: 14px; font-weight: 400 ">
          تطبيقات تقدم حلول وخدمات مميزه نوصي بتجربتها
        </h1>
      </div>
      <div class="d-flex justify-center">
        <v-card
          v-for="i in 4"
          :key="i"
          color="rgba(250, 250, 252, 0.93)"
          width="295.01px"
          height="169.67px"
          class="mx-10 mt-10"
          elevation="0"
        >
          <v-card-title>
            <v-img
              style="display: block"
              src="@/assets/mainlogo.png"
              max-width="50px"
              height="50px"
            />
            <span style="color: #8D5DA7; margin-top: -20px; margin-right: 10px"> قمره </span>
            <div
              class="mt-n5 mr-10"
              style="font-size: 14px; color: #54A787"
            >
              <v-icon
                color="#FFD12F"
                class="mb-1"
              >
                mdi-star
              </v-icon> 5
            </div>
          </v-card-title>
          <v-card-subtitle style="margin-right: 64px; margin-top: -40px">
            تطوير : <span style="color: #8D5DA7"> عمر سعد </span>
          </v-card-subtitle>
          <v-card-subtitle style="margin-right: 64px; margin-top: -10px; font-size: 10px">
            نظام الولاء الأمثل الذي يمكنك من رفع مبيعاتك
          </v-card-subtitle>
          <v-card-subtitle style="margin-right: 64px; margin-top: -30px; font-size: 10px">
            نظام الولاء الأمثل الذي يمكنك من رفع مبيعاتك
          </v-card-subtitle>
        </v-card>
      </div>
      <div class="d-flex justify-center mt-10">
        <v-btn
          color="#FFD12F"
          text
          style="font-weight: 600; font-size: 16px"
        >
          جميع التطبيقات
          <v-icon>mdi-chevron-left</v-icon>
        </v-btn>
      </div>
    </section>
    <section id="footer">
      <v-footer
        height="238"
        class="justify-center"
        color="#835D9D"
      >
        <social-media large />
      </v-footer>
    </section>
  </div>
</template>

<script>
  export default {
    name: 'CoreView',
    components: {
      SocialMedia: () => import('@/components/SocialMedia'),
    },
  }
</script>

<style scoped>
.app-bar {
  margin-right: 10%;
  margin-left: 10%;
  top: 0px;
  height: 8vh;
}
#welcome {
  height: 40vh;
}
#about {
  height: 50vh;
  margin-bottom: 20vh
}
#features {
  height: 60vh;
  background-color: rgba(250, 250, 252, 0.93);

}
#highlights {
  height: 80vh;
  padding-top: 15%;
}
</style>
