<script setup>  
</script>

<template>
  <v-app>
    
    <v-app-bar color="primary">
      <v-btn icon @click="console.log('back has been pressed')">
        <v-icon>mdi-arrow-left</v-icon>
      </v-btn>
      <v-toolbar-title>Annotation</v-toolbar-title>
    </v-app-bar>

    <v-bottom-navigation>

      <v-btn value="Participant_1">
        <span>Participant 1</span>
      </v-btn>

      <v-btn value="Participant_2">
        <span>Participant 2</span>
      </v-btn>
  
      <v-btn value="Participant_3">
        <span>Participant 3</span>
      </v-btn>

      <v-btn value="Participant_4">
        <span>participant_4</span>
      </v-btn>

    </v-bottom-navigation>
  </v-app>
</template>

