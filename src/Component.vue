<template>
  <div>
    Name: <slot name="name" v-bind="{ name }" />
  </div>
</template>

<script setup lang="ts">
import {ref} from 'vue';
const name = ref('My Name');
</script>
