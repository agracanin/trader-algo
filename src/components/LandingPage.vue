<script setup>
import Header from './Header.vue';
import Home from './Home.vue';
import Features from './Features.vue';
import Reasons from './Reasons.vue';
import Pricing from './Pricing.vue';
</script>

<template>
        <Header />
        <div class="main">
        <Home />
        <Features />
        <Reasons />
        <Pricing />
        </div>
</template>

<style scoped>
        .main {
                width: 60vw;
        }
</style>
