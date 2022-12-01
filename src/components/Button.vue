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
    },
    link: {
        type: String,
        default: ""
    },
    target:{
        type: String,
        default: "_self"
    }
})
</script>

<template>
    <a  :class="`btn ${type} ${color} `" :href="` ${link}`" :target="` ${target}`">
        {{ text }}
    </a>
</template>


  type 