<script
    setup
    lang="ts"
>

const props = defineProps<{msg: string}>()

</script>

<template>
  <div>
    {{msg}}
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
