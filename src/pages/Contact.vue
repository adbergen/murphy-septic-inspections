<template>
  <q-page>
    <div class="landing-image">
      <!-- Parallax with Header -->
      <div class="row q-pa-xl">
        <div
          class="q-pa-xl text-grey-9 text-center col-12 vertical-center flex flex-center"
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
              Contact
            </div>
          </q-intersection>
        </div>
      </div>
    </div>

    <!-- Expectations Section -->
    <div class="q-px-xl">
      <div class="q-pa-xl row q-mx-xl">
        <div class="col-12 text-body1 q-px-xl">
          <q-intersection
            once
            v-for="index in 1"
            :key="index"
            transition="slide-right"
            class="example-item"
          >
            <q-card class="q-pa-md">
              <q-card-section>
                <div class="text-h5 text-weight-bold text-green-9">
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
</style>
