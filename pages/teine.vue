<template>
    <!-- custom css that comes from style block at the bottom of this document -->
    
    <section class="grid grid-cols-3">
   
        <div v-for="item in mingidAndmed" :key="item.title"
        class="p-4 bg-white shadow rounded">
            <h1 class="custom-css" >
                {{ item.title }}
            </h1>
            <p>
                {{ item.descr }}
            </p>
        </div>
    </section>

    

</template>

<script setup>
    // use another layout from "/layouts/other-layout.vue"
    definePageMeta({
        layout: "other-layout",
    });

    const mingidAndmed= ref(
        [
            {
                "title": "Pealkiri 1",
                "descr": "Siin on mingi sisu"
            },
            {
                "title": "Pealkiri 2",
                "descr": "Siin on mingi sisu 2"
            },
            {
                "title": "Pealkiri 3",
                "descr": "Siin on mingi sisu 3"
            },
        ]
    
    );
</script>

<style scoped>
    .custom-css {
        font-size:2rem;
    }
</style>