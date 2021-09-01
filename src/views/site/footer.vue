<template>
    <v-footer app color="primary" dark absolute :footer="footer">
    <v-spacer></v-spacer>
    <v-col
      class="text-center"
      cols="12"
    >
      {{ new Date().getFullYear() + ' ' + footer }} — <strong>Vuefy</strong>
    </v-col>
    </v-footer>
</template>
<script>
export default {
  props: ['footer']
}
</script>
