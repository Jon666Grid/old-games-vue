<template>
  <v-container fluid>
    <v-app-bar color="orange" dark>
      <h1>RETRO GAMES FAN</h1>
      <v-spacer />
      <v-btn outlined class="ml-3">
        <router-link to="/">Главная</router-link>
      </v-btn>
      <v-btn outlined class="ml-3">
        <router-link to="/photo">галерея</router-link>
      </v-btn>
      <audio class="ml-3" controls="" name="media"><source src="https://c22.radioboss.fm/stream/144" type="audio/mpeg"></audio>
    </v-app-bar>
  </v-container>
</template>

<script>
import router from "@/router";

export default {
  components: { router },
};
</script>

<style lang="scss" scoped></style>
