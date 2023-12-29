<script setup>
import Header from './Header.vue';
import Home from './Home.vue';
import Features from './Features.vue';
import Reasons from './Reasons.vue';
</script>

<template>
        <Header />
        <div class="main">
        <Home />
        <Features />
        <Reasons />
        </div>
</template>

<style scoped>
        .main {
                width: 60vw;
        }
</style>
