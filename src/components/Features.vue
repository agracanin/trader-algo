<script setup>

</script>

<template>
<div class="features">
    <h1 class="section-heading">Features</h1>
    <div class="feature-list">
        <div class="row">
        <div class="feature">
            <div class="feature-img signal">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-shopping-cart"><circle cx="8" cy="21" r="1"></circle><circle cx="19" cy="21" r="1"></circle><path d="M2.05 2.05h2l2.66 12.42a2 2 0 0 0 2 1.58h9.78a2 2 0 0 0 1.95-1.57l1.65-7.43H5.12"></path></svg>
            </div>
            <div class="feature-text">
                <span class="feature-heading">Accurate Buy</span>
                <span class="feature-desc signal">
                    Sell chart signals
                </span>
            </div>
        </div>
        <div class="feature">
            <div class="feature-img">
                <!-- <img src="../assets/feature1.png" alt=""> -->
            </div>
            <div class="feature-text">
                <span class="feature-heading">Feature 1</span>
                <span class="feature-desc">
                    Lorem ipsum
                </span>
            </div>
        </div>
        <div class="feature">
            <div class="feature-img">
                <!-- <img src="../assets/feature1.png" alt=""> -->
            </div>
            <div class="feature-text">
                <span class="feature-heading">Feature 1</span>
                <span class="feature-desc">
                    Lorem ipsum
                </span>
            </div>
        </div>
    </div>
    <div class="row">
        <div class="feature">
            <div class="feature-img signal">
                <!-- <img src="../assets/feature1.png" alt=""> -->
            </div>
            <div class="feature-text">
                <span class="feature-heading">Accurate Buy</span>
                <span class="feature-desc signal">
                    Sell chart signals
                </span>
            </div>
        </div>
        <div class="feature">
            <div class="feature-img">
                <!-- <img src="../assets/feature1.png" alt=""> -->
            </div>
            <div class="feature-text">
                <span class="feature-heading">Feature 1</span>
                <span class="feature-desc">
                    Lorem ipsum
                </span>
            </div>
        </div>
        <div class="feature">
            <div class="feature-img">
                <!-- <img src="../assets/feature1.png" alt=""> -->
            </div>
            <div class="feature-text">
                <span class="feature-heading">Feature 1</span>
                <span class="feature-desc">
                    Lorem ipsum
                </span>
            </div>
        </div>
    </div>
    </div>
</div>
</template>

<style scoped>
    .section-heading{
        font-size: 3rem;
        color: white;
        padding-bottom: 1rem;
    }

    .features {
        padding: 2rem 5rem;
    }

    .feature-img {
        width: 60px;
        height: 60px;
        background-color: #00ff00;
        border-radius: 10px;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    
    .row {
        display: flex;
        justify-content: space-between;
        padding-bottom: 2rem;
    }

    .feature {
        display: flex;
        gap: 0.5em;
        align-items: center;
    }

    .feature-text {
        font-size: 1rem;
        display: flex;
        flex-direction: column;
        gap: 0.25em;
        font-weight: 600;
    }

    .signal {
        color: #885aef;
    }

    div.signal {
        background-color: #885aef;
    }
</style>
