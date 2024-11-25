<script setup>
import { useRoute } from 'vue-router'

const route = useRoute()
const data = route.query.data
</script>

<template>
    <main>
        <h1>hello face</h1>
        <p>Data: {{ data }}</p>
    </main>
</template>
