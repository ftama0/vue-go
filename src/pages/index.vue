<script setup>
import { useRouter } from 'vue-router'

const router = useRouter()

function goToAbsen() {
    router.push('/absen')
}
</script>

<template>
    <main>
        <h1>hello index</h1>
        <button @click="goToAbsen">Go to Absen</button>
    </main>
</template>
