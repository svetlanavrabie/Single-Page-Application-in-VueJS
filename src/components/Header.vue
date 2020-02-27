<template>
  <v-card>
    <v-toolbar color="blue darken-4" dark>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>

      <v-toolbar-title>Vuetify Template</v-toolbar-title>

      <v-spacer></v-spacer>
      <v-badge
        bordered
        bottom
        color="deep-purple accent-4"
        dot
        offset-x="10"
        offset-y="10"
      >
        <v-avatar size="40">
          <v-img src="https://cdn.vuetifyjs.com/images/lists/2.jpg"></v-img>
        </v-avatar>
      </v-badge>
      <div class="hidden-sm-and-down">
        <v-btn text>About</v-btn>
        <router-link to="/contact">
          <v-btn text>Contact</v-btn>
        </router-link>
        <router-link to="/login">
          <v-btn text>Login</v-btn>
        </router-link>
      </div>
    </v-toolbar>
  </v-card>
</template>

<script>
export default {
  name: "Header"
};
</script>
