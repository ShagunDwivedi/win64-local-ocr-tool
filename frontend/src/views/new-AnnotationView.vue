<script setup>
import { RouterView } from 'vue-router'
</script>

<template>
  <div class="annotationView-container">
    <header>
      <h1>Historical OCR Tool</h1>
    </header>
    <RouterView />
  </div>
</template>

<style>
.annotationView-container {
  padding: 1em;
}
</style>
