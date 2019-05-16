<template>
  <v-app>
    <v-toolbar app>
      <v-toolbar-title class="headline text-uppercase">
        <span>Vue</span>
        <span class="font-weight-light">MATERIAL DESIGN</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn flat href="https://github.com/vuetifyjs/vuetify/releases/latest" target="_blank">
        <span class="mr-2">Open me</span>
        <v-icon>open_in_new</v-icon>
      </v-btn>
    </v-toolbar>

    <div>
      <!-- Success Alert -->
      <v-alert :value="true" type="success">This is a success alert.</v-alert>
      <!-- Info Alert -->
      <v-alert :value="true" type="info">This is a info alert.</v-alert>

       <v-alert :value="true" type="success">This is a success alert.</v-alert>
    </div>
    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  components: {
    HelloWorld
  },
  data() {
    return {
      //
    };
  }
};
</script>
