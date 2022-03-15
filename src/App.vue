<template>
  <v-app>
  <!-- <v-navigation-drawer app> -->
    <!-- -->
  <!-- </v-navigation-drawer> -->

  <v-app-bar app>
    <v-app-bar-title>Marenas Beach Resort</v-app-bar-title>
  </v-app-bar>

  <!-- Sizes your content based upon application components -->
  <v-main>

    <!-- Provides the application the proper gutter -->
    <v-container fluid>

      <!-- If using vue-router -->
      <router-view></router-view>
    </v-container>
  </v-main>

  <v-footer app>
    <!-- -->
  </v-footer>
</v-app>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'App',

  data () {
    return {
      //
    }
  },
})
</script>
