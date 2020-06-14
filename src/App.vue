<template>
  <div id="app">
    <topbar />
    <navbar />
    <herosection />
    <support />
    <pricing />
    <p-h-ppower />
    <packeges />
    <supportframework />
    <p-h-pmodules />
    <spesificationserver />
    <share />
    <callcenter />
    <foot />
  </div>
</template>

<script>
import Topbar from "./components/Topbar.vue";
import Navbar from "./components/Navbar.vue";
import Herosection from "./components/Herosection.vue";
import Support from "./components/Support.vue";
import Pricing from "./components/Pricing.vue";
import PHPpower from "./components/PHPpower.vue";
import Packeges from "./components/Packeges.vue";
import Supportframework from "./components/Supportframework.vue";
import PHPmodules from "./components/PHPmodules.vue";
import Spesificationserver from "./components/Spesificationserver.vue";
import Share from "./components/Share.vue";
import Callcenter from "./components/Callcenter.vue";
import Foot from "./components/Foot.vue";

export default {
  name: "App",
  components: {
    Topbar,
    Navbar,
    Herosection,
    Support,
    Pricing,
    PHPpower,
    Packeges,
    Supportframework,
    PHPmodules,
    Spesificationserver,
    Share,
    Callcenter,
    Foot
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
/* @import "@/assets/css/style.css"; */
@font-face {
  font-family: "roboto";
  src: url("assets/fonts/roboto/Roboto-Regular.ttf");
  font-weight: normal;
  font-style: normal;
}
body {
  font-family: roboto;
}
</style>
