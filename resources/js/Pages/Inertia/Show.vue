<script setup>
defineProps({
    id: String,
    blog: Array,
});
</script>

<template>
    {{ id }}<br />
    {{ blog.title }}
</template>

<style></style>
