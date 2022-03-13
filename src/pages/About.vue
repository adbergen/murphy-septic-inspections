<template>
  <q-page>
    <div class="landing-image">
      <!-- Parallax with Header -->
      <div class="row q-pa-xl">
        <div
          class="q-pa-xl q-mt-xl text-grey-9 text-center col-12 vertical-center flex flex-center"
          style="letter-spacing: 0.05em"
        >
          <q-intersection
            once
            v-for="index in 1"
            :key="index"
            transition="scale"
            class="example-item"
          >
            <div
              class="text-h2 text-weight-bold flex flex-center"
              style="line-height: 150%"
            >
              About
            </div>
          </q-intersection>
        </div>
      </div>
    </div>

    <!-- About Section -->
    <div>
      <div class="q-px-xl">
        <div class="q-pa-xl row q-mx-xl">
          <div class="col-6 q-px-xl">
            <q-intersection
              once
              v-for="index in 1"
              :key="index"
              transition="slide-right"
              class="example-item"
            >
              <q-card class="transparent no-shadow">
                <q-card-section class="flex flex-center">
                  <q-img
                    width="70"
                    class="rounded-borders"
                    src="../assets/WhyCard.png"
                  />
                </q-card-section>
              </q-card>
            </q-intersection>
          </div>
          <div class="col-6 text-body1 q-px-xl flex flex-center">
            <q-intersection
              once
              v-for="index in 1"
              :key="index"
              transition="slide-left"
              class="example-item"
            >
              As an independent septic inspection company, Murphy's Septic
              Inspection LLC is certified in full-service, on-site wastewater
              system inspections for new real estate buyers and current
              homeowners. We proudly serve residential clients in all of New
              Jersey and swear by our green technology which utilizes
              state-of-the-art equipment and environmentally friendly products
              to get your job done. <br /><br />
              Current residential septic system requirements in New Jersey can
              vary by the municipality which can quickly become confusing and
              overwhelming. That's why new homeowners can rely on Murphy's to
              get the job done without hassle. We have inspected over 5,000
              homes and our primary duty is to educate you regarding the prop er
              use and maintenance of your septic system. <br /><br />
              With experience and knowledge about the unique inspection
              requirements for your local area, our highly trained inspectors
              can complete a thorough investigation in just a few short hours.
              We then provide you with a detailed inspection report and handle
              all the local reporting paperwork on your behalf, making the
              process as simple as can be.
            </q-intersection>
          </div>
        </div>
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
textarea {
  resize: none !important; /* this will disable resize for all textarea elements.  */
}
</style>
