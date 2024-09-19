<template>
  <div id="app">
    <div v-bind:id="elementId" v-bind:class="elementClass">Heading</div>
  </div>
</template>

<script setup>
import { ref } from "vue";
const elementId = "heading";
const elementClass = "heading";
</script>

<style></style>
