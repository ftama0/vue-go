<script setup>
import { useRouter } from 'vue-router'

const router = useRouter()

function goToAbsen() {
    router.push('/absen')
}

function goToFace() {
    router.push({ path: '/absen/face', query: { data: 'exampleData' } })
}
</script>

<template>
    <main>
        <h1>hello index</h1>
        <button @click="goToAbsen">Go to Absen</button>
        <button @click="goToFace">Go to Face with Data</button>
    </main>
</template>
