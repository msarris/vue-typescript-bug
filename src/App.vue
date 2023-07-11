<template>
  <component>
    <template #name="{name}">Value: {{ name }}</template>
  </component>
</template>

<script setup lang="ts">
import Component from "./Component.vue";
</script>

<style lang="scss">
div {
  font-size: 14px;
}
</style>
