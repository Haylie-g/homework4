<script setup>
    import { defineProps } from 'vue';

    const props  = defineProps({
        total: {
            type: Number,
            require: true,
        }
    })   

</script>

<template>
    <h4>Your Balance</h4>
    <h1 id="blannce">{{ total }}</h1>

</template>