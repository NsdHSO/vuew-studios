<script setup lang="ts">
import { ref } from 'vue'
import Friends from "./Friends.vue";

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
    <Friends msg="TEST"></Friends>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
