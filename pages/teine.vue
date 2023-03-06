<template>
    <!-- custom css that comes from style block at the bottom of this document -->
    <h1 class="custom-css">Teine</h1>
</template>

<script setup>
    // use another layout from "/layouts/other-layout.vue"
    definePageMeta({
        layout: "other-layout",
    });
</script>

<style scoped>
    .custom-css {
        font-size:5rem;
    }
</style>