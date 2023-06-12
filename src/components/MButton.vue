<script setup>
const props = defineProps({
    texto: String
})
</script>

<template>
    <button>{{ props.texto }}</button>
</template>

<style scoped> </style>