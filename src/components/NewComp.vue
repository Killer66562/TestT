<script setup lang="ts">
import { ref } from 'vue';
const num = ref(0);
const addOne = () => {
    num.value += 5;
}
const zero =() => {
    num.value=0;
}
</script>

<template>
    <h1>這是標題</h1>
    <h2>這是副標</h2>
    <h3>Value: {{ num }}</h3>
    <button type="button" @click="addOne">Add 1</button>
    <button type="button" @click="zero">zero</button>
</template>

<style></style>