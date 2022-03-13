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
              Services
            </div>
          </q-intersection>
        </div>
      </div>
    </div>

    <!-- Expectations Section -->
    <div class="q-px-xl">
      <div class="q-pa-xl row q-mx-xl">
        <div class="col-6 text-body1 q-px-xl">
          <q-intersection
            once
            v-for="index in 1"
            :key="index"
            transition="slide-right"
            class="example-item"
          >
            Murphy's Septic Inspections pledges to be an industry leader in New
            Jersey and follow the reporting standards of the NJ DEP strictly.
            Typically, our wastewater treatment system inspections start by
            obtaining the septic system designs from your local authority. If an
            escavator or additional equipment is necessary, our partners can
            provide this service as at an additional cost.<br /><br />
            Depending on the type of inspection, some septics require extensive
            digging due to various components being very deep and difficult to
            find. The underground utilities must be marked out, whether digging
            is done with a machine. We will advise you ahead of time what to
            expect, ask you to fill out a maintenance history questionnaire, and
            confirm with you before arrival.<br /><br />
            If heavier machinery is needed, our inspectors are capable of
            handling it with the most precise movements, leaving as little of an
            impact as possible while also making sure the system is running as
            it should. Our inspection crew is well-trained to handle all
            different types of
          </q-intersection>
        </div>
        <div class="col-6 text-body1 q-px-xl">
          <q-intersection
            once
            v-for="index in 1"
            :key="index"
            transition="slide-left"
            class="example-item"
          >
            septic systems and components of the system. The inspection process
            is usually quick but may take up to 2 hours to complete.<br /><br />
            We then open the septic tank, check the levels, and use an
            underground inline camera to inspect the connecting lines. We
            excavate down to the aggregate in the absorption area to inspect the
            stone and liquid level and also check the distribution boxes. Once
            the system is fully inspected, conclusions can be made with
            recommendations about the septic system's operation which determines
            whether the system in question will be able to serve the future
            needs of your family.<br /><br />
            If a problem is identified, we can help with referrals to repair
            services and direct you to helpful resources. We will work
            diligently with the local authorities and ensure your septic system
            is in the hands of qualified professionals who can restore it to its
            optimal working order to pass inspection. Once you receive your
            fully comprehensive report, no follow-up is needed but feel free to
            contact us if anything arises.
          </q-intersection>
        </div>
      </div>
    </div>
  </q-page>
</template>

<script>
import { defineComponent, ref } from "vue";
export default defineComponent({
  name: "services",
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
