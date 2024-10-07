<template>
    <button @click="clearValues">Limpar</button>
</template>

<script setup>
    const props = defineProps({
        clearValues: Function,
    })
</script>

<style scoped>
    button {
        width: 100%;
        margin-top: 1rem;
        padding: 5px;
        cursor: pointer;
        background-color: #302e6e;
        color: #fff;
        font-size: 1.5rem;
        border-color: transparent;
        transition: all .7s;
    }

    button:hover {
        background-color: #5c59a9;
    }
</style>