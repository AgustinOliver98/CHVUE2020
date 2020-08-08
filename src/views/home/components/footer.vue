<template>
  <div pa-1>
    <v-footer height="auto" app class="grey darken-3">
      <v-layout row wrap justify-center>
        <span class="white--text">&copy; {{ new Date().getFullYear() }}</span>
      </v-layout>
    </v-footer>
  </div>
</template>

<script lang="ts">
import { Vue, Component } from "vue-property-decorator";
@Component
export default class FooterClassComponent extends Vue {}
</script>