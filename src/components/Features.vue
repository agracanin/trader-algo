<script setup>

</script>

<template>
<div class="features">
    <h1 class="section-heading">Features</h1>
    <div class="feature-list">
        <div class="row">
        <div class="feature">
            <div class="feature-img feature-1">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="8" cy="21" r="1"></circle><circle cx="19" cy="21" r="1"></circle><path d="M2.05 2.05h2l2.66 12.42a2 2 0 0 0 2 1.58h9.78a2 2 0 0 0 1.95-1.57l1.65-7.43H5.12"></path></svg>
            </div>
            <div class="feature-text">
                <span class="feature-heading">Accurate buy</span>
                <span class="feature-desc feature-1-text">
                    Sell chart signals
                </span>
            </div>
        </div>
        <div class="feature">
            <div class="feature-img feature-2">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22 12h-4l-3 9L9 3l-3 9H2"></path></svg>
            </div>
            <div class="feature-text">
                <span class="feature-heading">Moving average</span>
                <span class="feature-desc feature-2-text">
                    Volatility clouds
                </span>
            </div>
        </div>
        <div class="feature">
            <div class="feature-img feature-3">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect width="8" height="8" x="3" y="3" rx="2"></rect><path d="M7 11v4a2 2 0 0 0 2 2h4"></path><rect width="8" height="8" x="13" y="13" rx="2"></rect></svg>
            </div>
            <div class="feature-text">
                <span class="feature-heading">Automated risk</span>
                <span class="feature-desc feature-3-text">
                    Management
                </span>
            </div>
        </div>
    </div>
    <div class="row">
        <div class="feature">
            <div class="feature-img feature-4">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect width="14" height="6" x="5" y="15" rx="2"></rect><rect width="10" height="6" x="7" y="3" rx="2"></rect><path d="M2 21h20"></path><path d="M2 3h20"></path></svg>
            </div>
            <div class="feature-text">
                <span class="feature-heading">Automated support</span>
                <span class="feature-desc feature-4-text">
                    Resistance lines
                </span>
            </div>
        </div>
        <div class="feature">
            <div class="feature-img feature-5">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect width="6" height="14" x="4" y="5" rx="2"></rect><rect width="6" height="10" x="14" y="7" rx="2"></rect><path d="M17 22v-5"></path><path d="M17 7V2"></path><path d="M7 22v-3"></path><path d="M7 5V2"></path></svg>
            </div>
            <div class="feature-text">
                <span class="feature-heading">Trending</span>
                <span class="feature-desc feature-5-text">
                    Candles
                </span>
            </div>
        </div>
        <div class="feature">
            <div class="feature-img feature-6">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 19a6 6 0 0 0-12 0"></path><circle cx="8" cy="9" r="4"></circle><polyline points="16 11 18 13 22 9"></polyline></svg>
            </div>
            <div class="feature-text">
                <span class="feature-heading">24/7</span>
                <span class="feature-desc feature-6-text">
                    Support
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
        width: 250px;
    }

    .feature-text {
        font-size: 1rem;
        display: flex;
        flex-direction: column;
        gap: 0.25em;
        font-weight: 600;
        text-align: left;
    }

    .feature-1-text {
        color: #0296fe;
    }

    .feature-1 {
        background: linear-gradient(to bottom right, #0296fe, #0279fe);
    }

    .feature-2 {
        background: linear-gradient(to bottom right, #885aef, #7033ff);
    }

    .feature-2-text {
        color: #885aef;
    }

    .feature-3 {
        background: linear-gradient(to bottom right, #07cafa, #2abaf3);
    }

    .feature-3-text {
        color: #07cafa;
    }

    .feature-4 {
        background: linear-gradient(to bottom right, #02d389, #01b677);
    }

    .feature-4-text {
        color: #02d389;
    }

    .feature-5 {
        background: linear-gradient(to bottom right, #f3c032, #fda70c);
    }

    .feature-5-text {
        color: #f3c032;
    }

    .feature-6 {
        background: linear-gradient(to bottom right, #f5386a, #ef315e);
    }

    .feature-6-text {
        color: #f5386a;
    }

</style>
