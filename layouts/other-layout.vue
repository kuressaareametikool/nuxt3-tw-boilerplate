<template>
    <!-- this is example 2-column layout -->
    <div class="grid grid-cols-2 h-screen">
        <div class="flex justify-center items-center bg-red-500">
            <!-- This is NavMain.vue from components folder -->
            <NavMain vertical="true" /> 
        </div>
        <div class="w-full max-w-2xl mx-auto px-4">
            <!-- Page is injected here -->
            <slot />
        </div>
    </div>
</template>