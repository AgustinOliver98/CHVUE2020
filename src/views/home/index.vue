<template>
  <div>
    <v-app-bar app color="white">
      <v-toolbar-title>CleanHouse</v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn class="ma-2" rounded elevation outlined>
        <v-icon left>mdi-magnify</v-icon>Buscar
      </v-btn>
      <v-spacer></v-spacer>
      <v-btn small elevation color>Iniciar Sesion</v-btn>
    </v-app-bar>
    <div>
      <v-main>
        <v-container fluid class="fill-height">
          <v-row>
            <v-col>
              <!-- DESCRIPCITION SECTION -->
            </v-col>
            <v-col>
              <!-- TODO:"REGISTER FORM COMPONENT" -->
            </v-col>
          </v-row>
        </v-container>
      </v-main>
    </div>
  </div>
</template>
<script lang="ts">
import Vue from "vue";
export default Vue.extend({});
</script>