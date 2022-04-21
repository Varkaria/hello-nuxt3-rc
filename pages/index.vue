<script lang="ts" setup>
definePageMeta({ layout: 'default' })

const number: number = ref(2)
</script>

<template>
    <div>hi {{ number }}</div>

    <button @click="number++">
        Click me
    </button>
</template>