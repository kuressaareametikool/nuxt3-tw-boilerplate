<script setup>
    const props = defineProps({
        vertical : {
            default: false,
            type: Boolean
        }
    })
</script>
<template>
    <nav class="flex gap-4 p-2 bg-blue-500
        lg:bg-red-500
    "
    :class="vertical ? 'flex-col' : 'flex-row'"
    >
        <NuxtLink to="/">Avaleht</NuxtLink>
        <NuxtLink to="/teine">Teine</NuxtLink>
    </nav>
</template>

