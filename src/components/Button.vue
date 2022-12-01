<script setup>
defineProps({
    text: {
        type: String,
        required: true
    },
    color: {
        type: String,
        default: "primary"
    },
    type: {
        type: String,
        default: "filled"
    }
})
</script>

<template>
    <a href="" :class="`btn ${type} ${color} `">
        {{ text }}
    </a>
</template>


  