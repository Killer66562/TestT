<script setup lang="ts">
import { ref } from 'vue';
const num = ref(0);
const addOne = () => {
    num.value++;
}
</script>

<template>
    <h1>這是標題</h1>
    <h2>這是副標</h2>
    <h3>Value: {{ num }}</h3>
    <button type="button" @click="addOne">Add 1</button>
</template>

<style></style>