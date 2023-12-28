<script setup>

</script>

<template>
<div class="header">
    <div class="logo">
        <span class="logo-text text1">Trader</span>
        <span class="logo-text text2">Algo</span>
    </div>

    <nav class="header-nav">
        <ul class="nav-list">
            <li><a href="#">Home</a></li>
            <li><a href="#">Pricing</a></li>
            <li><a href="#">Features</a></li>
            <li><a href="#">Tutorial</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>

    <div class="heading-cta">
        <button class="cta-button">Buy Access</button>
    </div>
</div>
</template>

<style scoped>
.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #0e1320;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
    padding: 1em 5em;
}

.nav-list {
    display: flex;
    list-style: none;
    gap: 1rem;
    font-size: 0.9rem;
}

a 
{
    text-decoration: none;
    color: darkgray;
}
a:hover 
{
    color: white;
}

.logo-text {
    font-size: 1.5rem;
    color: white;
}

.text1 {
    font-weight: 700;
}

.text2 {
    font-weight: 100;
}

.cta-button {
    padding: 1rem 1.25rem;
    border: none;
    border-radius: 5px;
    background-color: #00e016;
    color: white;
    font-weight: bold;
    font-size: 1rem;
    cursor: pointer;
}

.cta-button:hover {
    opacity: 0.8;
}
</style>
