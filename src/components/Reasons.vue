<script>

</script>

<template>
<div class="reasons">
    <h1>Reasons to use <span class="green">TraderAlgo</span></h1>
    <div class="reason-container">
        <div class="reason">
        <h2>Make Profits</h2>
        <p class="reason-desc">By using our simple buy & sell signals, you can grow your trading account like many of our users. TradingAlgo has a proven win rate of 92%.</p>
        <div class="number-overlay">
            1
        </div>
    </div>
        <div class="reason">
        <h2>Affordable</h2>
        <p class="reason-desc">We can confidently say we are the most affordable indicator of our caliber. We’re here to provide a low barrier of entry to new aspiring traders.</p>
        <div class="number-overlay">
            2
        </div>
    </div>
        <div class="reason">
        <h2>All Markets And Timeframes</h2>
        <p class="reason-desc">Our indicator works on absolutely any market or timeframe, it has been tested and proven to be profitable in all conditions. You can trade stocks, crypto, forex, etc.</p>
        <div class="number-overlay">
            3
        </div>
    </div>
        <div class="reason">
        <h2>Simplicity</h2>
        <p class="reason-desc">TraderAlgo is super easy to use as our goal is to take the complexity out of trading, our indicator makes the chart easy to read.</p>
        <div class="number-overlay">
            4
        </div>
    </div>
    </div>
</div>
</template>

<style scoped>

.reasons {
    padding-left: 5em;
}
h2 {
    font-size: 1.5rem;
    color: white;
    font-weight: 700;
}
.reason-container {
    display: flex;
    flex-wrap: wrap;
    gap: 2rem;
}
    


.reasons h1 {
    font-size: 3rem;
    color: white;
    padding-bottom: 1rem;
}

.green {
    color: #00ff00;
}


.reason {
    position: relative;
    display: flex;
    flex-direction: column;
    gap: 1rem;
    padding: 3rem 2rem;
    background-color: rgb(14, 19, 29);
    border-radius: 10px;
    width: 500px;
}

.number-overlay {
    position: absolute;
    top: 0;
    right: 10px;
    font-size: 150px;
    color: gray;
    opacity: 30%;
    font-weight: 300;
}

.reason-desc {
    font-size: 1rem;
    color: white;
    font-weight: 200;
    padding-right: 4em;
}

</style>