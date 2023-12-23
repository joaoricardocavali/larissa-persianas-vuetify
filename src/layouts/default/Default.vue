<template>
  <v-app>
    <topbar />

    <default-view />
  </v-app>
</template>

<script lang="ts" setup>
  import Topbar from '@/components/Topbar.vue';
  import DefaultView from './View.vue'
</script>
