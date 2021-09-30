<template>
  <v-container fluid class="red pa-0 fill-height">
    <v-row class="ma-0 d-flex fill-height justify-center">
      <v-col cols="3" class="pa-0"
        ><v-container class="blue darken-3 fill-height justify-center">
          <v-card flat width="100%" height="80%" class="text-center">
            <v-card-text>OIOI</v-card-text>
          </v-card>
        </v-container>
      </v-col>
      <v-col cols="6" class="pa-0">
        <v-container class="pink fill-height justify-center">
          <v-avatar color="blue" width="200" height="200">
            <!-- <v-icon size="50%">mdi-account-circle</v-icon> -->
          </v-avatar>
        </v-container>
      </v-col>
      <v-col cols="3" class="pa-0">
        <v-container class="blue darken-3 fill-height align-start">
          <v-card flat width="100%" height="80%" class="">
            <v-toolbar flat color="light-green accent-4">
              <v-toolbar-title class="flex text-center">
                Your Todo list
              </v-toolbar-title>
            </v-toolbar>
            <v-text-field class=" pa-0 mt-0 ml-3 mr-3" />
            <v-list two-line subheader> </v-list>
          </v-card>
        </v-container>
      </v-col>
    </v-row>
  </v-container>
</template>
<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  data() {
    return {
      todos: [],

      newTodo: '',
      step: '',
    }
  },
})
</script>
