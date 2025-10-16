
<script setup>
    import { ref } from 'vue'
</script>

<template>
    <header>
        
        <img src="@/assets/logo_vue_300px.png" alt="vue logo" />
       
        <h1>Hi, I'm <span class="highlight">Vue</span></h1>
    </header>
</template>

<style scoped>
    header img {
        height: 100px;
    }
    header h1 {
        font-size: 2rem;
        color: #34495e;
        margin-top: 10px;
    }
</style>