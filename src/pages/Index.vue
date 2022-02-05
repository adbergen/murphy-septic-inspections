<template>
  <q-page>
    <!-- Parallax with Header -->
    <div class="q-pb-md row">
      <q-img width="100%" height="960px" src="../assets/LandingBackground.png">
        <h1
          class="text-white text-weight-bolder row justify-center full-height full-width text-center items-center q-my-xl"
          style="line-height: 1.2; letter-spacing: 0.05em"
        >
          Qualified Residential <br />Septic System Inspections
        </h1>
      </q-img>
    </div>

    <!-- About Section -->
    <div
      class="row text-center justify-center text-h3 text-green-10 q-pt-xl text-weight-bold"
    >
      Buying or Selling Your Home?
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
            homeowners and prospective real estate pur- chasers. An onsite
            wastewater treatment and disposal system, or what is more commonly
            referred to as a Sep- tic System, may be the most expensive single
            compo- nent of your home. Therefore, if you want to save your- self
            some trouble in the future it's crucial that you know its condition
            and routinely have it checked.<br />
            <br />Getting a septic inspection provides you with informa- tion
            about the septic system components and their cur- rent operating
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
            tial septic system inspection before completion. Mur- phy's
            certified and licensed inspectors will inspect your residential
            septic system thoroughly and make the pro- cess quick and painless.
            <br />
            <br />Our inspections typically take about 3 hours though it is
            important to note every system is different and finding the
            components, exposing them, and dealing with any issues that may
            arise can take varied amounts of time. Your residential septic
            inspection report can be ready within 24 hours but due to COVID
            impacting the review process it could take up to 7 business days for
            it to be- come available.
          </q-intersection>
        </div>
      </div>
    </div>
    <div class="row q-pa-xl">
      <div class="col-6 q-pa-xl">
        <q-card class="col-6 q-pa-lg transparent no-shadow">
          <q-card-section class="col-7 flex flex-center">
            <q-img
              width="70"
              class="rounded-borders"
              src="../assets/HomeownersCard.png"
            />
          </q-card-section>
        </q-card>
      </div>
      <div class="col-6 q-pa-xl">
        <q-card class="col-6 q-pa-lg transparent no-shadow">
          <q-card-section class="col-7 flex flex-center">
            <q-img
              width="70"
              class="rounded-borders"
              src="../assets/NewRealEstateCard.png"
            />
          </q-card-section>
        </q-card>
      </div>
      <div class="col-6 q-pa-xl">
        <q-card class="col-6 q-pa-lg transparent no-shadow">
          <q-card-section class="col-7 flex flex-center">
            <q-img
              width="70"
              class="rounded-borders"
              src="../assets/AboutCard.png"
            />
          </q-card-section>
        </q-card>
      </div>
      <div class="col-6 q-pa-xl">
        <q-card class="col-6 q-pa-lg transparent no-shadow">
          <q-card-section class="col-7 flex flex-center">
            <q-img
              width="70"
              class="rounded-borders"
              src="../assets/ContactCard.png"
            />
          </q-card-section>
        </q-card>
      </div>
    </div>

    <!-- About Section -->
    <div class="bg-green">
      <div
        class="row text-center justify-center text-h3 text-white q-pt-xl text-weight-bold"
      >
        Why Choose Murphys?
      </div>
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
          <div class="col-6 text-body1 q-px-xl">
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

    <!-- Expectations Section -->
    <div
      class="row text-center justify-center text-h3 text-green-10 q-pt-xl text-weight-bold"
    >
      What to Expect?
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
            Murphy's Septic Inspections pledges to be an industry leader in New
            Jersey by XXXX and follow the reporting standards of the NJ DEP
            strictly. Typically, our wastewa- ter treatment system inspections
            start by obtaining the septic system designs from your local
            authority. We then head out to mark the underground utilities which
            en- sures that no buried cables, pipes, or wires will be dam- aged
            and no utilities such as gas, electricity, cable, or telephone will
            be disrupted when digging is involved.<br /><br />
            Depending on the type of inspection, some septics re- quire
            extensive digging due to various components be- ing very deep and
            difficult to find. The underground utili- ties must be marked out,
            whether digging is done with a shovel or a machine. We will advise
            you ahead of time what to expect, ask you to fill out a maintenance
            history questionnaire, and confirm with you before arrival.<br /><br />
            If heavier machinery is needed, our inspectors are ca- pable of
            handling it with the most precise movements, leaving as little of an
            impact as possible while also mak- ing sure the system is running as
            it should. Our inspec- tion crew is well-trained to handle all
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
            septic systems and components of the system. The in- spection
            process is usually quick but may take up to 3 hours to complete.<br /><br />
            We then open the septic tank, check the levels, and use an
            underground inline camera to inspect the connecting lines. We
            excavate down to the aggregate in the absorp- tion area to inspect
            the stone and liquid level and also check the distribution boxes.
            Once the system is fully inspected, conclusions can be made with
            recommen- dations about the septic system's operation which de-
            termines whether the system in question will be able to serve the
            future needs of your family.<br /><br />
            If a problem is identified, we can help with referrals to re- pair
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
    <div
      class="row text-center justify-center text-h3 text-green-10 q-pt-xl text-weight-bold"
    >
      Areas Served
    </div>
    <div class="q-px-xl">
      <div class="q-pa-xl row q-mx-xl">
        <div class="col-6 text-body1 text-green text-center q-px-xl">
          <q-intersection
            once
            v-for="index in 1"
            :key="index"
            transition="slide-right"
            class="example-item"
          >
            Atlantic, Bergen, Burlington, Camden, Cape May, Cumberland, Essex,
            Gloucester, Hudson, Hunterdon, Mercer, Middlesex, Monmouth, Morris,
            Ocean, Passaic, Salem, Somerset, Sussex Union & Warren Counties
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
            With over 5 years of experience in residential septic sys- tem
            inspection, Murphy's Septic Inspection goes above and beyond to make
            your residential inspection quick and easy. Our friendly and
            knowledgable inspectors fol- low the reporting standards of the NJ
            DEP. We are happy to offer recommendations on advanced services and
            have access to a network of industry professionals who can help
            prolong your system's life. Schedule your free consultation today
            with one of our friendly inspectors.
          </q-intersection>
        </div>
      </div>
    </div>

    <!-- About Section -->
    <div class="bg-green">
      <div
        class="row text-center justify-center text-h3 text-white q-pt-xl text-weight-bold"
      >
        Need a Home Septic Inspection? <br />
        Murphy's Can Be There
      </div>
      <div class="q-px-xl">
        <div class="q-pa-xl row q-mx-xl">
          <div class="col-6 text-body1 q-px-xl">
            <q-intersection
              once
              v-for="index in 1"
              :key="index"
              transition="slide-left"
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
    </div>

    <!-- Contact Section -->
    <div class="q-pa-xl row bg-grey-3">
      <div class="col-12 text-h5 text-weight-bold q-pa-xl">
        Want to talk about your project?
      </div>
      <div class="col-12">
        <q-intersection
          once
          v-for="index in 1"
          :key="index"
          transition="scale"
          class="example-item"
        >
          <div class="row">
            <div class="col-1 q-pa-md text-right">
              <q-avatar size="80px">
                <!-- <img src="../assets/new.png" /> -->
              </q-avatar>
            </div>
            <div class="col-3 q-pa-lg text-center text-body1">
              Hi, I’m Anthony, CEO at Gifted Software. Drop us a line at
              <a href="info@giftedsoftware.com">info@giftedsoftware.com</a> or
              fill in the form to the right and we’ll get in touch with you
              soon!
            </div>
            <div class="col-8">
              <div class="row">
                <q-input
                  bg-color="white"
                  class="col-6 q-pa-lg"
                  outlined
                  v-model="text"
                  label="Full Name"
                />
                <q-input
                  bg-color="white"
                  class="col-6 q-pa-lg"
                  outlined
                  v-model="text"
                  label="Email"
                />
              </div>
              <div class="row">
                <q-input
                  bg-color="white"
                  class="col-6 q-pa-lg"
                  outlined
                  v-model="text"
                  label="Phone Number"
                />
                <q-input
                  bg-color="white"
                  class="col-6 q-pa-lg"
                  outlined
                  v-model="text"
                  label="Company (if applicable)"
                />
              </div>
              <div class="row">
                <q-input
                  bg-color="white"
                  class="col-12 q-pa-lg"
                  outlined
                  v-model="text"
                  type="textarea"
                  label="Describe your project or idea"
                />
              </div>
              <div class="row">
                <div class="col-12 q-pa-lg text-right">
                  <q-btn label="Send" type="submit" color="primary" />
                </div>
              </div>
            </div>
          </div>
        </q-intersection>
      </div>
    </div>
  </q-page>
</template>

<script>
import { defineComponent, ref } from "vue";
export default defineComponent({
  name: "Home",
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
