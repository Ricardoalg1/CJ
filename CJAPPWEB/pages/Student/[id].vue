<template>
    <div>
        <h1> {{message}}</h1>
    </div>
</template>

<script setup>
const route = useRoute()
const message = computed(()=> `My Student ID is ${route.params.id}`)
</script>