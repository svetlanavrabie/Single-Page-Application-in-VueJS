<template>
  <v-app id="app">
    <Header />
    <router-view />
    <Footer />
  </v-app>
</template>
<script>
import Header from "./components/Header";
import Footer from "./components/Footer";
export default {
  name: "app",
  components: { Header, Footer }
};
</script>
