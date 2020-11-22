<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      ColorSchemer
      <v-color-picker
        v-model="rgb"
        dot-size="25"
        swatches-max-height="200"
      ></v-color-picker>
      {{ rgb }}
    </v-col>
  </v-row>
</template>

<script lang="ts">
export default {
  data: () => ({
    rgb: {},
  }),
}
</script>
