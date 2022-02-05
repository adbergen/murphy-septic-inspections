<template>
  <q-page>
    <!-- Parallax with Header -->
    <div class="q-pb-md row">
      <q-img
        width="100%"
        height="960px"
        src="https://www.thespruce.com/thmb/bZ8LaJANplZ50PHeY9RFdiP0EME=/941x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/small-bathroom-design-tips-4125936-hero-38951b2471944ff9b36691f1081f7619.jpg"
      >
        <div
          class="text-white text-weight-bolder row justify-center full-height full-width text-center items-center q-my-xl"
          style="line-height: 1.2; letter-spacing: 0.05em"
        >
          Qualified Residential <br />Septic System Inspections
        </div>
        <h1
          class="text-white text-weight-bolder row justify-center full-height full-width text-center items-center q-my-xl"
          style="line-height: 1.2; letter-spacing: 0.05em"
        >
          Qualified Residential <br />Septic System Inspections
        </h1>
      </q-img>
    </div>

    <!-- About Section -->
    <div class="q-pa-xl row">
      <div class="col-6 text-h4 text-center q-pa-xl">
        <q-intersection
          once
          v-for="index in 1"
          :key="index"
          transition="slide-right"
          class="example-item"
        >
          Imagine your project into reality.
        </q-intersection>
      </div>
      <div class="col-6 text-body1">
        <q-intersection
          once
          v-for="index in 1"
          :key="index"
          transition="slide-left"
          class="example-item"
        >
          Utilizing next generation technologies, we deliver sophisticated
          webites and software products. We build scaleable and maintainable
          solutions that support your requirements. From simple websites for
          your business to complex, cloud-based software applications, no
          project is too big or small. We offer custom built solutions tailored
          to your project in mind.
        </q-intersection>
      </div>
    </div>

    <!-- Case Studies Section -->
    <div class="q-pa-xl row bg-grey-3">
      <div class="col-12 text-h5 text-weight-bold q-pa-xl">Case Studies</div>
      <div class="col-12">
        <q-intersection
          once
          v-for="index in 1"
          :key="index"
          transition="scale"
          class="example-item"
          ><div class="row">
            <q-card
              class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-xs-4 q-pa-lg transparent no-shadow"
            >
              <q-card-section class="col-7 flex flex-center">
                <q-img
                  width="70"
                  class="rounded-borders"
                  src="https://cdn.quasar.dev/img/parallax2.jpg"
                />
              </q-card-section>
              <q-card-section>
                <q-card-section class="q-pt-xs">
                  <div class="text-h5 q-mt-sm q-mb-xs">Surgeon Hunter</div>
                  <div class="text-caption text-grey">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                    do eiusmod tempor incididunt ut labore et dolore magna
                    aliqua.
                  </div>
                </q-card-section>
              </q-card-section>
              <q-separator />
              <q-card-actions align="right">
                <q-btn flat round icon="event" />
                <q-btn flat> View Case Study </q-btn>
              </q-card-actions>
            </q-card>
            <q-card
              class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-xs-4 q-pa-lg transparent no-shadow"
            >
              <q-card-section class="col-7 flex flex-center">
                <q-img
                  width="70"
                  class="rounded-borders"
                  src="https://cdn.quasar.dev/img/parallax2.jpg"
                />
              </q-card-section>
              <q-card-section>
                <q-card-section class="q-pt-xs">
                  <div class="text-h5 q-mt-sm q-mb-xs">Meka Alarm Systems</div>
                  <div class="text-caption text-grey">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                    do eiusmod tempor incididunt ut labore et dolore magna
                    aliqua.
                  </div>
                </q-card-section>
              </q-card-section>
              <q-separator />
              <q-card-actions align="right">
                <q-btn flat round icon="event" />
                <q-btn flat> View Case Study </q-btn>
              </q-card-actions>
            </q-card>
            <q-card
              class="col-xl-4 col-lg-4 col-md-4 col-sm-4 col-xs-4 q-pa-lg transparent no-shadow"
            >
              <q-card-section class="col-7 flex flex-center">
                <q-img
                  width="70"
                  class="rounded-borders"
                  src="https://media.istockphoto.com/photos/coming-soon-neon-sign-the-banner-shining-light-signboard-collection-picture-id1332167985?b=1&k=20&m=1332167985&s=170667a&w=0&h=O-084eNJBhGZGJbJvNvUC1P6d4aSo6XkV4Kom7ZZcIQ="
                />
              </q-card-section>
              <q-card-section>
                <q-card-section class="q-pt-xs">
                  <div class="text-h5 q-mt-sm q-mb-xs">Coming Soon</div>
                  <div class="text-caption text-grey">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
                    do eiusmod tempor incididunt ut labore et dolore magna
                    aliqua.
                  </div>
                </q-card-section>
              </q-card-section>
              <q-separator />
              <q-card-actions align="right">
                <q-btn flat round icon="event" />
                <q-btn flat> View Case Study </q-btn>
              </q-card-actions>
            </q-card>
          </div>
        </q-intersection>
      </div>
    </div>

    <!-- Services Section -->
    <div class="q-pa-xl row">
      <div class="col-12 text-h5 text-weight-bold q-pa-xl">Services</div>
      <div class="col-xl-12 col-lg-12">
        <q-intersection
          once
          v-for="index in 1"
          :key="index"
          transition="scale"
          class="example-item"
          ><div class="row flex flex-center">
            <q-card
              class="col-xl-2 col-lg-2 col-md-4 col-sm-4 col-xs-4 q-pa-lg transparent no-shadow"
            >
              <q-card-section
                ><q-icon size="xl" name="o_psychology" />
              </q-card-section>

              <q-card-section class="q-pt-xs">
                <div class="text-h5 q-mt-sm q-mb-xs">Ideation & Strategy</div>
                <div class="text-caption text-grey">
                  Reach new business opportunities or test your existing product
                  ideas
                </div>
              </q-card-section>
            </q-card>
            <q-card
              class="col-xl-2 col-lg-2 col-md-4 col-sm-4 col-xs-4 q-pa-lg transparent no-shadow"
            >
              <q-card-section
                ><q-icon size="xl" name="o_brush" />
              </q-card-section>

              <q-card-section class="q-pt-xs">
                <div class="text-h5 q-mt-sm q-mb-xs">Product Design</div>
                <div class="text-caption text-grey">
                  Create a modern digital product or polish your exisiting one
                </div>
              </q-card-section>
            </q-card>
            <q-card
              class="col-xl-2 col-lg-2 col-md-4 col-sm-4 col-xs-4 q-pa-lg transparent no-shadow"
            >
              <q-card-section
                ><q-icon size="xl" name="o_devices" />
              </q-card-section>

              <q-card-section class="q-pt-xs">
                <div class="text-h5 q-mt-sm q-mb-xs">Web & Mobile</div>
                <div class="text-caption text-grey">
                  Pursue a modern, tailor-made approach with mobile and web apps
                </div>
              </q-card-section>
            </q-card>
            <q-card
              class="col-xl-2 col-lg-2 col-md-4 col-sm-4 col-xs-4 q-pa-lg transparent no-shadow"
            >
              <q-card-section
                ><q-icon size="xl" name="o_smart_toy" />
              </q-card-section>

              <q-card-section class="q-pt-xs">
                <div class="text-h5 q-mt-sm q-mb-xs">
                  Artificial Intelligence
                </div>
                <div class="text-caption text-grey">
                  Automate your processes and get data-drive business insights
                </div>
              </q-card-section>
            </q-card>
            <q-card
              class="col-xl-2 col-lg-2 col-md-4 col-sm-4 col-xs-4 q-pa-lg transparent no-shadow"
            >
              <q-card-section
                ><q-icon size="xl" name="o_cloud" />
              </q-card-section>

              <q-card-section class="q-pt-xs">
                <div class="text-h5 q-mt-sm q-mb-xs">Cloud Services</div>
                <div class="text-caption text-grey">
                  Create lightweight, scaleable, and easily accessible cloud
                  solutions
                </div>
              </q-card-section>
            </q-card>
          </div>
        </q-intersection>
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
