<template>
  <v-app>
    <v-app-bar app color="primary" dark></v-app-bar>
      <v-toolbar-title>Most Used Words</v-toolbar-title>
    <v-content>
      <Home />
    </v-content>
  </v-app>
</template>

<script>
import Home from './components/Home'

export default {
  name: 'App',

  components: {
    Home
  },

  data: () => ({
    //
  }),
};
</script>
