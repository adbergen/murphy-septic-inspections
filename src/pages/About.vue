<template>
  <q-page>
    <div class="banner">
      <!-- Parallax with Header -->
      <div class="row q-pa-xl">
        <div
          class="q-pa-xl text-white text-center col-12 vertical-center flex flex-center text-decoration"
          style="letter-spacing: 0.05em"
        >
          <q-intersection
            once
            v-for="index in 1"
            :key="index"
            transition="scale"
            class="example-item"
          >
            <div class="text-h3 text-weight-bold flex flex-center">About</div>
            <q-separator color="white" />
          </q-intersection>
        </div>
      </div>
    </div>

    <!-- About Section -->

    <div class="row">
      <q-img
        width="70"
        class="rounded-borders col-6"
        src="../assets/WhyCard.png"
      />

      <div class="col-6 text-body1 q-px-xl flex flex-center">
        <q-intersection
          once
          v-for="index in 1"
          :key="index"
          transition="slide-left"
          class="example-item"
        >
          <div class="text-h4 q-pb-md">Meet your Septic Inspector</div>
          As an independent septic inspection company, Murphy's Septic
          Inspection LLC is certified in full-service, on-site wastewater system
          inspections for new real estate buyers and current homeowners. We
          proudly serve residential clients in all of New Jersey and swear by
          our green technology which utilizes state-of-the-art equipment and
          environmentally friendly products to get your job done. <br /><br />
          Current residential septic system requirements in New Jersey can vary
          by the municipality which can quickly become confusing and
          overwhelming. That's why new homeowners can rely on Murphy's to get
          the job done without hassle. We have inspected over 5,000 homes and
          our primary duty is to educate you regarding the prop er use and
          maintenance of your septic system. <br /><br />
          With experience and knowledge about the unique inspection requirements
          for your local area, our highly trained inspectors can complete a
          thorough investigation in just a few short hours. We then provide you
          with a detailed inspection report and handle all the local reporting
          paperwork on your behalf, making the process as simple as can be.
        </q-intersection>
      </div>
    </div>
  </q-page>
</template>

<script>
import { defineComponent, ref } from "vue";
export default defineComponent({
  name: "about",
  setup() {
    const socialLinks = ref([
      {
        name: "fab fa-facebook",
        class: "q-pa-sm",
        size: "lg",
        route: "/",
      },
      {
        name: "fab fa-instagram",
        class: "q-pa-sm",
        size: "lg",
        route: "/",
      },
      {
        name: "fab fa-twitter",
        class: "q-pa-sm",
        size: "lg",
        route: "/",
      },
      {
        name: "fab fa-linkedin",
        class: "q-pa-sm",
        size: "lg",
        route: "/",
      },
    ]);
    return {
      socialLinks,
      text: ref(""),
    };
  },
});
</script>

<style>
.banner {
  background-image: url("../assets/GreenBanner.png");
  background-repeat: no-repeat;
  background-size: 100% 150%;
}
</style>
