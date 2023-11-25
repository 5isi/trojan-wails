<script lang="ts" setup>
</script>

<template>
  <div id="app">
    <h1>Trojan-Wails</h1>
    <v-container>
      <v-row>
        <v-col cols="12" sm="12">
          <v-text-field label="Remote Server Address" />
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12" sm="12">
          <v-text-field label="Remote Server Port" />
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12" sm="12">
          <v-text-field label="Password" />
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12" sm="12">
          <v-text-field label="SNI" />
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12" sm="12">
          <v-text-field label="Bind Local Port" />
        </v-col>
      </v-row>
      <v-row>
        <v-col cols="12" sm="12">
          <v-btn color="primary">Start Trojan</v-btn>
          <v-btn color="secondary" class="ml-5">Kill Trojan</v-btn>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<style>
body {
    background-color: white;
}
</style>
