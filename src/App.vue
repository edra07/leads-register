<template>
  <v-app>
    <v-app-bar
      app
      color="pink darken-3"
      dark
    >
      <div class="d-flex align-center">
        <h1>Pitts & Collies</h1>
      </div>

      <v-spacer></v-spacer>

      <v-btn
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
      >
        <span class="mr-2">Latest Release</span>
        <v-icon>mdi-open-in-new</v-icon>
      </v-btn>
    </v-app-bar>

    <v-content>
      <Index/>
    </v-content>
  </v-app>
</template>

<script>
import Index from './components/Index';

export default {
  name: 'App',

  components: {
    Index,
  },

  data: () => ({
    //
  }),
};
</script>
