<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
    <v-app-bar-nav-icon></v-app-bar-nav-icon>
    <v-toolbar-title>Collapsing Bars</v-toolbar-title>
    <v-spacer/>
    <v-btn icon to="/about">
        <v-icon>mdi-magnify</v-icon>
    </v-btn>
    </v-app-bar>
    <v-content>
      <router-view/>
    </v-content>
    <v-footer app color="primary" dark absolute>
    <v-spacer></v-spacer>
    <v-col
      class="text-center"
      cols="12"
    >
      {{ new Date().getFullYear() }} — <strong>Vuetify</strong>
    </v-col>
    </v-footer>
  </v-app>
</template>

<script>

export default {
  name: 'App'
}
</script>
