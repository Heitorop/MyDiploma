<template>
  <v-app>
    <v-header />

    <default-view />
    <custom-footer />
  </v-app>
</template>

<script lang="ts" setup>
import VHeader from './VHeader.vue'
import CustomFooter from './CustomFooter.vue'
import DefaultView from './View.vue'
</script>
