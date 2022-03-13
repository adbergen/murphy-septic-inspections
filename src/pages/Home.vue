<template>
  <q-page class="fonting">
    <!-- Landing View -->
    <div class="landing-image">
      <div class="row q-pa-xl">
        <div
          class="q-pa-xl text-grey-9 text-center col-8 vertical-center flex flex-center"
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
              Septic System Inspections

              <br />
              <div class="text-green-9 text-weight-bold text-h4">
                Serving All of New Jersey
              </div>
            </div>
          </q-intersection>
        </div>
        <!-- Callback Card -->
        <div class="q-pa-xl flex flex-center q-mt-xl col-4">
          <q-intersection
            once
            v-for="index in 1"
            :key="index"
            transition="scale"
            class="example-item"
          >
            <q-card class="q-pa-md">
              <q-card-section>
                <div class="text-h5 text-weight-bold text-green-9">
                  Request a callback
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

    <!-- About Section -->
    <div
      class="row q-pt-xl text-center justify-center text-h3 text-green-10 text-weight-bold"
    >
      Looking for a Septic Inspector?
    </div>
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
            We perform residential septic system inspections for current
            homeowners and prospective real estate purchasers. An onsite
            wastewater treatment and disposal system, or what is more commonly
            referred to as a Septic System, may be the most expensive single
            component of your home. Therefore, if you want to save yourself some
            trouble in the future it's crucial that you know its condition and
            routinely have it checked.<br />
            <br />Getting a septic inspection provides you with information
            about the septic system components and their current operating
            conditions. Local municipalities and New Jersey state regulations
            require a professional residen-
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
            tial septic system inspection before completion. Murphy's certified
            and licensed inspectors will inspect your residential septic system
            thoroughly and make the process quick and painless.
            <br />
            <br />Our inspections typically take about 3 hours though it is
            important to note every system is different and finding the
            components, exposing them, and dealing with any issues that may
            arise can take varied amounts of time. Your residential septic
            inspection report can be ready within 24 hours but due to COVID
            impacting the review process it could take up to 7 business days for
            it to become available.
          </q-intersection>
        </div>
      </div>
    </div>
    <div class="q-px-xl bg-green">
      <div class="row q-pa-xl q-mx-xl">
        <div class="col-4 q-pa-xl">
          <q-card flat>
            <q-img :ratio="16 / 9" src="../assets/HomeownersCard.png" />
            <div class="bg-grey-1">
              <q-card-section>
                <q-btn
                  fab
                  color="green-10"
                  icon="info"
                  class="absolute"
                  style="
                    top: 0;
                    right: 50%;
                    left: 44%;
                    transform: translateY(-50%);
                  "
                />
                <q-card-section class="text-h5 text-center">
                  <div>About Murphy's</div>
                </q-card-section>

                <q-card-section class="q-pt-none text-center text-subtitle1">
                  <div>
                    Complete system inspections are done for several reasons and
                    we perform residential septic system inspections for both
                    current homeowners and prospective real estate purchasers.
                  </div>
                </q-card-section>
              </q-card-section>
            </div>
          </q-card>
        </div>
        <div class="col-4 q-pa-xl">
          <q-card flat>
            <q-img :ratio="16 / 9" src="../assets/AboutCard.png" />
            <div class="bg-grey-1">
              <q-card-section>
                <q-btn
                  fab
                  color="green-10"
                  icon="home"
                  class="absolute"
                  style="
                    top: 0;
                    right: 50%;
                    left: 44%;
                    transform: translateY(-50%);
                  "
                />
                <q-card-section class="text-h5 text-center">
                  <div>Services</div>
                </q-card-section>

                <q-card-section class="q-pt-none text-center text-subtitle1">
                  <div>
                    An onsite wastewater treatment and disposal system, or
                    Septic System, may be the most expensive single component of
                    your home. For home sellers, a pre-listing inspection can
                    ensure that there are no surprises once their home is put on
                    the market.
                  </div>
                </q-card-section>
              </q-card-section>
            </div>
          </q-card>
        </div>

        <div class="col-4 q-pa-xl">
          <q-card flat>
            <q-img :ratio="16 / 9" src="../assets/ContactCard.png" />
            <div class="bg-grey-1">
              <q-card-section>
                <q-btn
                  fab
                  color="green-10"
                  icon="phone"
                  class="absolute"
                  style="
                    top: 0;
                    right: 50%;
                    left: 44%;
                    transform: translateY(-50%);
                  "
                />
                <q-card-section class="text-h5 text-center">
                  <div>Contact</div>
                </q-card-section>

                <q-card-section class="q-pt-none text-center text-subtitle1">
                  <div>
                    Feel confident choosing Murphy's Septic Inspections. Buying
                    or selling, we do not offer any type of septic repair work
                    so you do not have to worry about Murphy's finding problems
                    that don't exist.
                  </div>
                </q-card-section>
              </q-card-section>
            </div>
          </q-card>
        </div>
      </div>
    </div>

    <!-- Areas Served Section -->
    <div
      class="row text-center justify-center text-h3 text-green-10 q-pt-xl text-weight-bold"
    >
      Areas Served
    </div>
    <div class="q-px-xl">
      <div class="q-pa-xl row q-mx-xl">
        <div
          class="col-6 text-h6 text-green-10 text-weight-bolder text-center q-pa-xl"
        >
          <q-intersection
            once
            v-for="index in 1"
            :key="index"
            transition="slide-right"
            class="example-item"
          >
            <div class="text-green-10 text-weight-bolder">
              Atlantic, Bergen, Burlington,<br />
              Camden, Cape May, Cumberland, Essex,<br />
              Gloucester, Hudson, Hunterdon, Mercer,<br />
              Middlesex, Monmouth, Morris, Ocean,<br />
              Passaic, Salem, Somerset, Sussex,<br />
              Union, & Warren Counties
            </div>
            <br />
            <q-separator />
            <div class="text-black text-weight-regular">
              <br />
              With over 5 years of experience in residential septic system
              inspection, Murphy's Septic Inspection goes above and beyond to
              make your residential inspection quick and easy. Our friendly and
              knowledgable inspectors follow the reporting standards of the NJ
              DEP. We are happy to offer recommendations on advanced services
              and have access to a network of industry professionals who can
              help prolong your system's life. Schedule your free consultation
              today with one of our friendly inspectors.
            </div>
          </q-intersection>
        </div>
        <div class="col-6 q-pa-xl text-center">
          <q-intersection
            once
            v-for="index in 1"
            :key="index"
            transition="slide-left"
            class="example-item"
          >
            <q-img width="50%" src="../assets/NewJerseyCounties.png" />
          </q-intersection>
        </div>
      </div>
    </div>

    <!-- Contact Section -->
    <div class="bg-green">
      <div
        class="row text-center justify-center text-h3 text-white q-pt-xl text-weight-bold"
      >
        Need a Home Septic Inspection? <br />
        Murphy's Can Be There
      </div>
      <div class="q-px-xl">
        <div class="q-pa-xl row q-mx-xl text-white">
          <div class="col-6 text-body1 q-px-xl">
            <q-intersection
              once
              v-for="index in 1"
              :key="index"
              transition="slide-right"
              class="example-item"
            >
              Murphy Septic Inspection, LLC is a member of the National
              Association of Wastewater Technicians or NAWT. All of our septic
              inspections are performed in strict conformance to the NAWT’s
              Inspection Standards by certified NAWT inspectors. Due to these
              high standards, these specifications have been described by many
              as the Industry Standard for an on-lot residential septic system
              inspection in New Jersey and around the nation.
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
              A comprehensive septic inspection provides you with valuable
              information about the present condition of the system, however, it
              is important to note that it is not a warranty that guarantees
              that the system will function properly for any period in the
              future. All of our expert residential septic system inspectors are
              highly trained and certified to inspect, identify problems and
              provide solutions. Reach out to see why Murphy is the right
              choice.
            </q-intersection>
          </div>
        </div>
      </div>
      <div
        class="row text-center justify-center text-h6 text-white q-pt-xl text-weight-bold"
      >
        Want to Learn More?
      </div>
      <div class="q-pa-xl row q-mx-xl">
        <div class="col-4 text-body1 q-px-md">
          <q-intersection
            once
            v-for="index in 1"
            :key="index"
            transition="slide-left"
            class="example-item"
          >
            <q-input
              label-color="white"
              filled
              v-model="text"
              label="Full Name"
            />
          </q-intersection>
        </div>
        <div class="col-4 text-body1 q-px-md">
          <q-intersection
            once
            v-for="index in 1"
            :key="index"
            transition="slide-left"
            class="example-item"
          >
            <q-input
              label-color="white"
              filled
              v-model="text"
              label="Phone Number"
            />
          </q-intersection>
        </div>
        <div class="col-4 text-body1 q-px-md">
          <q-intersection
            once
            v-for="index in 1"
            :key="index"
            transition="slide-left"
            class="example-item"
          >
            <q-input label-color="white" filled v-model="text" label="Email" />
          </q-intersection>
        </div>
        <q-btn
          class="col-12 q-pa-md q-my-md"
          color="white"
          text-color="green"
          label="Submit"
        />
      </div>
    </div>
  </q-page>
</template>

<script>
import { defineComponent, ref } from "vue";
export default defineComponent({
  name: "Home",
  setup() {
    return {
      text: ref(""),
    };
  },
});
</script>

<style>
textarea {
  resize: none !important; /* this will disable resize for all textarea elements.  */
}

.landing-image {
  background-image: url("../assets/LandingBackground.png");
  background-repeat: no-repeat;
  background-size: 100% 150%;
}
</style>
