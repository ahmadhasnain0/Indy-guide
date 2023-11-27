<template>
    <div id="app" class="wrapper">
        <div class="home-main">
<Nav/>
<Header/>
<Destination />
<Community />
<Guide/>
<Guests/>
<Feature/>
<Footer/>
          </div>
    </div>
</template>

<script setup>
import Nav from "./src/components/nav.vue"
import Header from "./src/components/header.vue"
import Destination from "./src/components/destination.vue"
import Community from "./src/components/travel-community.vue"
import Guide from "./src/components/guide.vue"
import Guests from "./src/components/guests.vue"
import Feature from "./src/components/feature-in.vue"
import Footer from "./src/components/fotter.vue"



</script>
<style scoped>
@import "./src/assets/scss/style.scss";
body {
    margin: 0!important;
    font-family: -apple-system, BlinkMacSystemFont, Segoe UI, Roboto,
        Helvetica Neue, Arial, Noto Sans, sans-serif, Apple Color Emoji,
        Segoe UI Emoji, Segoe UI Symbol, Noto Color Emoji;
    font-size: 1rem;
    font-weight: 400;
    line-height: 1.5;
    color: #212529;
    text-align: left;
    background-color: #fff;
    padding: 0!important;
    display: block;

}
</style>
