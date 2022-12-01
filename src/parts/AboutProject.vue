<script setup>
    import Button from '../components/Button.vue';
</script>

<template>
    <div class="aboutproject">
        <div class="text">
            <h1>What is this project?</h1>
            <p>
                This is a folder completely configured to start well with Vue 3 and SASS. 
            </p>
            <p>
                The SASS configuration is the same as on my Web-starter project.
            </p>
            <p>Si vous ne connaissez pas mon projet Web-starter et/ou que vous n'êtes pas à l'aise avec le SASS je vous invite à voir mon projet en cliquant juste en dessous</p>
            <Button text="Voir le projet Web-starter" link="https://github.com/Olivieroy/web-starter" target="_blank" color="secondary"/>
        </div>
        <img src="../../public/img/VueSASS.png" alt="" class="img">
    </div>
</template>