<template>
  <q-layout view="lHh Lpr lff">
    <q-header class="bg-white">
      <q-toolbar>
        <q-toolbar-title
          class="q-ml-xl q-pt-md q-pb-md text-h4 text-weight-bold"
        >
          <q-img
            style="height: 60px; max-width: 300px"
            src="../assets/headerLogo.png"
          />
        </q-toolbar-title>

        <q-tabs
          v-model="headerNav"
          indicator-color="green"
          active-color="green"
          class="bg-transparent text-black"
        >
          <q-route-tab label="Home" to="/" exact />
          <q-route-tab label="About" to="/about" exact />
          <q-route-tab label="Services" to="/services" exact />
          <q-route-tab label="Contact" to="/contact" exact />
        </q-tabs>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>
    <!-- Footer -->
    <q-footer class="bg-grey-10 row" position="bottom">
      <div class="col-4 q-py-xl">
        <q-tabs
          v-model="footerNav"
          vertical
          dense
          indicator-color="transparent"
          active-color="green"
          class="bg-transparent text-white"
        >
          <q-route-tab label="Home" to="/" exact />
          <q-route-tab label="About" to="/about" exact />
          <q-route-tab label="Services" to="/services" exact />
          <q-route-tab label="Contact" to="/contact" exact />
        </q-tabs>
      </div>
      <div class="col-4">
        <div class="q-py-xl col-12 text-center">
          <q-img
            style="height: 142px; max-width: 273px"
            src="../assets/footerLogo.png"
          />
        </div>
        <div class="col-12 text-center q-pb-md">
          <q-btn rounded label="Book a Consultation" outline color="white" />
        </div>
      </div>
      <div class="col-4">
        <div class="q-pt-xl col-12 text-body1 text-center">
          For Even More <br />
          <a
            class="text-green"
            style="text-decoration: none; color: inherit"
            href="/contact"
            >Sign Up</a
          >
          For Our <br />Newsletter
        </div>
        <div class="q-py-xl col-12 text-center">
          <q-btn
            rounded
            size="md"
            color="green-9"
            label="@Murphysepticinspec"
          />
        </div>
      </div>
      <div class="col-12">
        <!-- Social Links -->
        <div class="q-py-sm col-12 text-center">
          <q-btn
            flat
            v-for="link in socialLinks"
            :key="link.name"
            :size="link.size"
            :class="link.class"
            :icon="link.name"
            type="a"
            :href="link.route"
            target="__blank"
          />
        </div>
        <div class="col-12 text-center" style="word-spacing: 3px">
          <p>© Murphy Septic Inspections LLC 2021</p>
        </div>
      </div>
    </q-footer>
  </q-layout>
</template>

<script>
import { defineComponent, ref } from "vue";

export default defineComponent({
  name: "MainLayout",

  setup() {
    const socialLinks = ref([
      {
        name: "fab fa-facebook",
        class: "q-pa-sm",
        size: "lg",
        route: "",
      },
      {
        name: "fab fa-instagram",
        class: "q-pa-sm",
        size: "lg",
        route: "",
      },
      {
        name: "fab fa-twitter",
        class: "q-pa-sm",
        size: "lg",
        route: "",
      },
      {
        name: "fab fa-linkedin",
        class: "q-pa-sm",
        size: "lg",
        route: "",
      },
    ]);
    return {
      socialLinks,
      headerNav: ref("home"),
      footerNav: ref("home"),
    };
  },
});
</script>
