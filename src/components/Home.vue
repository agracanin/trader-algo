<script setup>

</script>

<template>
<div class="home-container">
    <div class="home-left">
        <div class="home-heading">
            <h1 class="heading">
                Trading Made Easy <span class="heading-green">TraderAlgo</span>
            </h1>
        </div>

        <div class="sub-heading">
            <p class="sub-heading-text 1">
                The greatest trading algorithm on the market!
            </p>

            <div class="heading-buttons">
                <button class="heading-button cta">Buy Access</button>
                <button class="heading-button discord">Join Discord
                    <img src="../assets/discord.svg" alt="">
                </button>
            </div>

            <p class="sub-heading-text 2">
                Gain an edge in the markets by simplifying your trading experience. 🚀
            </p>
        </div>
    </div>

    <div class="home-right">
        <div class="image-container">
            <img src="../assets/laptop.png" alt="">
        </div>
    </div>
</div>
<div class="testimonial">
    <div class="testimonial-text">
        <p class="testimonial-text">
            “TradingAlgo has completely taken the complication out of my trading process and is more profitable than my previous strategies. I recommend it to anyone at any skill level.”
        </p>
        <span class="author">- @dummyUser4212</span>
    </div>

    <div class="iphone-img">
        <img src="../assets/iphone.png" alt="">
    </div>
    </div>
</template>

<style scoped>
.home-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 5em;
}

.home-left {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    gap: 2rem;
}

.heading {
    font-size: 3rem;
    color: white;
}

.heading-green {
    color: #00ff00;
}

.sub-heading {
    display: flex;
    flex-direction: column;
    gap: 1rem;
}

.sub-heading-text {
    font-size: 0.9rem;
    color: rgb(138 138 138);
}

.heading-buttons {
    display: flex;
    gap: 1rem;
}

.heading-button {
    padding: 1rem 1.25rem;
    border: none;
    border-radius: 5px;
    color: black;
    font-weight: bold;
    font-size: 1rem;
    cursor: pointer;
}

.heading-button:hover {
    opacity: 0.8;
}

.cta {
    background-color: #00e016;
}

.discord {
    background-color: #7289da;
    color: white;
    display: flex;
    gap: 10px;
    align-items: center;
    justify-content: center;
    text-align: center;
}

.discord > img {
    width: 25px;
}

.testimonial {
    display: flex;
    background-color: rgba(35, 40, 53, 0.596);
    margin: 0 5rem;
    padding: 0.5em 2em;
    align-items: center;
    height: 250px;
    position: relative;
}

.testimonial-text {
    font-size: 1.1rem;
    color: white;
    font-weight: 300;
    margin-right: 2rem;
    width: 400px;
    padding-bottom: 1rem;
}


.iphone-img{
    position: absolute;
    width: 350px;
    height: 260px;
    overflow: hidden;
    top: -10px;
    right: 60px;
}

.author {
    color: #00ff00;
}
</style>
