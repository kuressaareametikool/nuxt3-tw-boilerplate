<template>
    <div class="relative">
        <!-- This is NavMain.vue from components folder -->
        <NavMain /> 
        <div class="w-full max-w-2xl mx-auto px-4">
            <!-- Page is injected here -->
            <slot />
        </div>
    </div>
</template>