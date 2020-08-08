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
        <v-container fluid class="fill-height home-container">
          <v-row>
            <v-col>
              <description />
            </v-col>
            <v-col>
              <register />
            </v-col>
          </v-row>
        </v-container>
      </v-main>
    </div>
  </div>
</template>
<script lang="ts">
import { Vue, Component } from "vue-property-decorator";
import register from "./components/register.vue";
import description from "./components/description.vue";

@Component({
  components: { register, description },
})
export default class HomeViewClassComponent extends Vue {}
</script>

<style lang="scss">
.home-container {
  background-color: lightcoral;
  margin: auto;
}
</style>