<template>
  <q-layout view="lHh Lpr lff">
    <q-header :class="{ 'transparent text-black': $route.path == '/' }">
      <q-toolbar :class="{ 'bg-white text-black': $route.path != '/' }">
        <q-toolbar-title
          class="q-ml-xl q-pt-md q-pb-md text-h4 text-weight-bold"
        >
          Murphy Septic Inspections
        </q-toolbar-title>

        <q-btn stretch flat label="Home" to="/" />
        <q-btn stretch flat label="About" to="/about" />
        <q-btn stretch flat label="Buyers" to="/buyers" />
        <q-btn stretch flat label="Homeowners" to="/homeowners" />
        <q-btn stretch flat label="Contact" to="/contact" />
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>
    <q-footer class="bg-black" position="bottom">
      <!-- Social Links -->
      <div class="q-pa-md text-center">
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
      <div class="row">
        <!-- HOPE Identity -->
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
        route: "https://www.linkedin.com/company/giftedsoftware",
      },
    ]);
    return {
      socialLinks,
    };
  },
});
</script>

<style>
.q-page-container {
  padding-top: 0 !important;
}
</style>
