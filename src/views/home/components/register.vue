<template>
  <div>
    <v-form>
      <v-text-field name="name" label="label" value="value" single-line></v-text-field>
      <v-text-field name="name" label="label" value="value" single-line></v-text-field>
      <v-text-field name="name" label="label" value="value" single-line></v-text-field>
      <v-text-field name="name" label="label" value="value" single-line></v-text-field>
      <v-text-field name="name" label="label" value="value" single-line></v-text-field>
    </v-form>
  </div>
</template>

<script lang="ts">
import { Vue, Component } from "vue-property-decorator";
@Component
export default class RegisterFormComponent extends Vue {}
</script>