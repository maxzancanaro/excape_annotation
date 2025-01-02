<script setup>  
</script>

<template>
  <v-app>
  <v-container> 
  <v-row justify="center">
  <v-col cols="12" md="8" sm="4">
    <v-app-bar color="primary">
      <v-btn icon @click="console.log('back has been pressed')">
        <v-btn icon="mdi-arrow-left"></v-btn>
      </v-btn>
      <v-toolbar-title>Annotation 1.1</v-toolbar-title>
    </v-app-bar>
  </v-col>
  </v-row>

  <v-row justify="center">
  <v-col cols="12" md="8" sm="4">
      <v-card>
        <v-card-title>Welcome</v-card-title>
        <v-card-text>
                This is a mobile-friendly app built with Vuetify.
        </v-card-text>
        <v-card-actions>
            <v-btn color="primary">Get Started</v-btn>
        </v-card-actions>
      </v-card>
  </v-col>
  </v-row>
    
  <v-row justify="center">
  <v-col cols="12" md="8" sm="4">
    <v-bottom-navigation>
      <v-btn value="Participant_1">
        <span>Part. 1</span>
      </v-btn>

      <v-btn value="Participant_2">
        <span>Part. 2</span>
      </v-btn>
  
      <v-btn value="Participant_3">
        <span>Part. 3</span>
      </v-btn>

      <v-btn value="Participant_4">
        <span>Part. 4</span>
      </v-btn>

    </v-bottom-navigation>
  </v-col>
  </v-row>
  </v-container>
  </v-app>
</template>

