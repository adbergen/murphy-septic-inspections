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
            <div class="text-h3 text-weight-bold flex flex-center">Contact</div>
            <q-separator color="white" />
          </q-intersection>
        </div>
      </div>
    </div>

    <!-- Contact Section -->
    <div class="q-px-xl">
      <div class="q-pa-xl row q-mx-xl">
        <div class="col-4 text-body1 q-px-xl">
          <q-intersection
            once
            v-for="index in 1"
            :key="index"
            transition="slide-right"
            class="example-item"
          >
            <q-card>
              <q-card-section class="text-center">
                <q-img src="../assets/headerLogo.png" />
              </q-card-section>

              <q-list>
                <q-item>
                  <q-item-section avatar>
                    <q-avatar color="green-9" text-color="white" icon="email" />
                  </q-item-section>
                  <q-item-section class="text-h5">Email</q-item-section>
                </q-item>

                <q-item>
                  <q-item-section class="text-body1"
                    >info@murphysepticinspections.com</q-item-section
                  >
                </q-item>
                <q-item>
                  <q-item-section avatar>
                    <q-avatar color="green-9" text-color="white" icon="phone" />
                  </q-item-section>
                  <q-item-section class="text-h5">Phone Number</q-item-section>
                </q-item>

                <q-item>
                  <q-item-section class="text-body1"
                    >555-555-5555</q-item-section
                  >
                </q-item>
                <q-item>
                  <q-item-section avatar>
                    <q-avatar color="green-9" text-color="white" icon="place" />
                  </q-item-section>
                  <q-item-section class="text-h5">Service Area</q-item-section>
                </q-item>

                <q-item>
                  <q-item-section class="text-body1"
                    >Serving all counties within New Jersey</q-item-section
                  >
                </q-item>
              </q-list>
            </q-card>
          </q-intersection>
        </div>
        <div class="col-8 text-body1 q-px-xl">
          <q-intersection
            once
            v-for="index in 1"
            :key="index"
            transition="slide-right"
            class="example-item"
          >
            <q-card class="q-pa-md">
              <q-card-section>
                <div class="text-h4 text-weight-bold text-green-9 text-center">
                  Send us a message
                </div>
              </q-card-section>

              <q-card-section>
                <q-input label="Name" class="q-px-xl" outlined />
              </q-card-section>
              <q-card-section>
                <q-input label="Email Address" class="q-px-xl" outlined />
              </q-card-section>
              <q-card-section>
                <q-input label="Phone Number" class="q-px-xl" outlined />
              </q-card-section>

              <q-card-section>
                <q-input
                  label="Message"
                  class="q-px-xl"
                  type="textarea"
                  outlined
                />
              </q-card-section>

              <q-card-actions class="q-px-xl">
                <q-btn class="col-12 bg-green-9 text-white" flat>Submit</q-btn>
              </q-card-actions>
              <q-card-section class="text-body1 text-center">
                Our team will be in touch as soon as possible to discuss your
                needs.
              </q-card-section>
            </q-card>
          </q-intersection>
        </div>
      </div>
    </div>
  </q-page>
</template>

<script>
import { defineComponent, ref } from "vue";
export default defineComponent({
  name: "contact",
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
.banner {
  background-image: url("../assets/GreenBanner.png");
  background-repeat: no-repeat;
  background-size: 100% 150%;
}
</style>
