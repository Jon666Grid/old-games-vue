<template>
  <v-app>
    <Navbar/>
    <router-view />
  </v-app>
</template>

<script>
import Navbar from "@/components/Navbar";
import router from "./router";

export default {
  name: "App",
  components: {
    Navbar,
    router
}
};
</script>
