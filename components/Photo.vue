<script setup>
const props = defineProps({
    src: String
})
</script>

<template>
    <img :src="src" />
</template>