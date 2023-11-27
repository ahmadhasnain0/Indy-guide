<template>
    <div>
        <nav class="navigation-indy position-fixed w-100 p-0 " :class="{ 'navigation-indy': true, 'nav-style': scrolled }">
            <div class="d-flex flex-wrap align-items-center container-fluid"> <a href="/"
                    class="logo mx-lg-0 mx-md-0 mx-sm-0 mx-auto outline-none"><img src="../assets/images/logo-main.png"
                        alt="image slot"></a>
                <ul class="left-sidebar list-unstyled mb-0 d-lg-flex d-none flex-wrap">
                    <li>
                        <div id="dropdown-aria" class="dropdown b-dropdown dropdown-custom btn-no-styling btn-group">
                            <button id="dropdown-aria__BV_toggle_" aria-haspopup="menu" aria-expanded="false" type="button"
                                class="btn dropdown-toggle btn-secondary bg-transparent p-0 border-0"
                                @click="toggleDropdown">
                                DESTINATIONS
                            </button>
                            <ul id="dropMenu_content" role="menu" tabindex="-1" aria-labelledby="dropdown-aria__BV_toggle_"
                                class="dropdown-menu destination-dropdown dropdown-arrow rounded-0"
                                :style="{ display: showDropdown ? 'block' : 'none' }" x-placement="top-start" >
                                <div class="px-0 container">
                                    <div class="custom-accordion pt-5">
                                        <h4 class="d-block text-secondary mb-4">Select Your Destination</h4>
                                        <div class="row align-items-center">
                                            <div class="col-3 h-340">
                                                <div class="border-0 gray-btn mb-3">
                                                    <div class="d-flex align-items-center flex-wrap"><a href="/kyrgyzstan"
                                                            class="text-capitalize text-truncate float-left text-dark pl-3">
                                                            Kyrgyzstan </a> </div>
                                                </div>
                                                <div class="border-0 gray-btn mb-3">
                                                    <div class="d-flex align-items-center flex-wrap"><a href="/uzbekistan"
                                                            class="text-capitalize text-truncate float-left text-dark pl-3">
                                                            Uzbekistan </a> </div>
                                                </div>
                                                <div class="border-0 gray-btn mb-3">
                                                    <div class="d-flex align-items-center flex-wrap"><a href="/kazakhstan"
                                                            class="text-capitalize text-truncate float-left text-dark pl-3">
                                                            Kazakhstan </a> <button block="" href="#"
                                                            class="no-focus position-relative ml-auto border-0 bg-transparent collapsed"
                                                            aria-expanded="false" aria-controls="destination1_2"
                                                            style="overflow-anchor: none;"><img
                                                                src="../assets/images/svgs/arrow-dark-gray.svg"
                                                                alt="Arrow"></button></div>
                                                    <div id="destination1_2" role="tabpanel" style="display: none;"
                                                        class="collapse">
                                                        <div class="accordion-body">
                                                            <ul class="list-unstyled list-countries pl-3 pt-2">
                                                                <li class="clearfix d-flex flex-wrap align-items-center"><a
                                                                        href="/almaty-region" class="float-left"><img
                                                                            src="https://indyguide-web-development.s3.us-east-2.amazonaws.com/destinations/1586989329_country_icon.jpg"
                                                                            alt="country-image"
                                                                            class="rounded-circle image-cover"></a> <a
                                                                        href="/almaty-region"
                                                                        class="float-left max-50 py-0 pl-3 text-capitalize">Almaty
                                                                        Region</a></li>
                                                                <li class="clearfix d-flex flex-wrap align-items-center"><a
                                                                        href="/nur-sultan" class="float-left"><img
                                                                            src="https://indyguide-web-development.s3.us-east-2.amazonaws.com/destinations/1586989212_country_icon.JPG"
                                                                            alt="country-image"
                                                                            class="rounded-circle image-cover"></a> <a
                                                                        href="/nur-sultan"
                                                                        class="float-left max-50 py-0 pl-3 text-capitalize">Nur
                                                                        Sultan</a></li>
                                                                <li class="clearfix d-flex flex-wrap align-items-center"><a
                                                                        href="/turkestan" class="float-left"><img
                                                                            src="https://indyguide-web-development.s3.us-east-2.amazonaws.com/destinations/1586988606_country_icon.JPG"
                                                                            alt="country-image"
                                                                            class="rounded-circle image-cover"></a> <a
                                                                        href="/turkestan"
                                                                        class="float-left max-50 py-0 pl-3 text-capitalize">Turkestan</a>
                                                                </li>
                                                                <li class="clearfix d-flex flex-wrap align-items-center"><a
                                                                        href="/mangystau" class="float-left"><img
                                                                            src="https://indyguide-web-development.s3.us-east-2.amazonaws.com/destinations/1586950027_country_icon.jpg"
                                                                            alt="country-image"
                                                                            class="rounded-circle image-cover"></a> <a
                                                                        href="/mangystau"
                                                                        class="float-left max-50 py-0 pl-3 text-capitalize">Mangystau</a>
                                                                </li>
                                                                <li class="clearfix d-flex flex-wrap align-items-center"><a
                                                                        href="/east-kazakhstan" class="float-left"><img
                                                                            src="https://indyguide-web-development.s3.us-east-2.amazonaws.com/destinations/1587283563_country_icon.jpg"
                                                                            alt="country-image"
                                                                            class="rounded-circle image-cover"></a> <a
                                                                        href="/east-kazakhstan"
                                                                        class="float-left max-50 py-0 pl-3 text-capitalize">East
                                                                        Kazakhstan</a></li>
                                                            </ul>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div class="border-0 gray-btn mb-3">
                                                    <div class="d-flex align-items-center flex-wrap"><a href="/mongolia"
                                                            class="text-capitalize text-truncate float-left text-dark pl-3">
                                                            Mongolia </a> <button block="" href="#"
                                                            class="no-focus position-relative ml-auto border-0 bg-transparent collapsed"
                                                            aria-expanded="false" aria-controls="destination1_3"
                                                            style="overflow-anchor: none;"><img
                                                                src="../assets/images/svgs/arrow-dark-gray.svg"
                                                                alt="Arrow"></button></div>
                                                    <div id="destination1_3" class="collapse" role="tabpanel"
                                                        style="display: none;">
                                                        <div class="accordion-body">
                                                            <ul class="list-unstyled list-countries pl-3 pt-2">
                                                                <li class="clearfix d-flex flex-wrap align-items-center"><a
                                                                        href="/altai" class="float-left"><img
                                                                            src="https://indyguide-web-development.s3.us-east-2.amazonaws.com/destinations/1590746450_country_icon.jpg"
                                                                            alt="country-image"
                                                                            class="rounded-circle image-cover"></a> <a
                                                                        href="/altai"
                                                                        class="float-left max-50 py-0 pl-3 text-capitalize">Altai</a>
                                                                </li>
                                                                <li class="clearfix d-flex flex-wrap align-items-center"><a
                                                                        href="/gobi-desert" class="float-left"><img
                                                                            src="https://indyguide-web-development.s3.us-east-2.amazonaws.com/destinations/1609713025_country_icon.jpg"
                                                                            alt="country-image"
                                                                            class="rounded-circle image-cover"></a> <a
                                                                        href="/gobi-desert"
                                                                        class="float-left max-50 py-0 pl-3 text-capitalize">Gobi
                                                                        Desert</a></li>
                                                            </ul>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="col-3 h-340">
                                                <div class="border-0 gray-btn mb-3">
                                                    <div class="d-flex align-items-center flex-wrap"><a href="/tajikistan"
                                                            class="text-capitalize text-truncate float-left text-dark pl-3">
                                                            Tajikistan </a> </div>
                                                </div>
                                                <div class="border-0 gray-btn mb-3">
                                                    <div class="d-flex align-items-center flex-wrap"><a href="/pakistan"
                                                            class="text-capitalize text-truncate float-left text-dark pl-3">
                                                            Pakistan </a> </div>
                                                </div>
                                                <div class="border-0 gray-btn mb-3">
                                                    <div class="d-flex align-items-center flex-wrap"><a href="/india"
                                                            class="text-capitalize text-truncate float-left text-dark pl-3">
                                                            India </a> <button block="" href="#"
                                                            class="no-focus position-relative ml-auto border-0 bg-transparent collapsed"
                                                            aria-expanded="false" aria-controls="destination2_6"
                                                            style="overflow-anchor: none;"><img
                                                                src="../assets/images/svgs/arrow-dark-gray.svg"
                                                                alt="Arrow"></button></div>
                                                    <div id="destination2_6" role="tabpanel" style="display: none;"
                                                        class="collapse">
                                                        <div class="accordion-body">
                                                            <ul class="list-unstyled list-countries pl-3 pt-2">
                                                                <li class="clearfix d-flex flex-wrap align-items-center"><a
                                                                        href="/leh" class="float-left"><img
                                                                            src="https://indyguide-web-development.s3.us-east-2.amazonaws.com/destinations/1682342682_country_icon.jpg"
                                                                            alt="country-image"
                                                                            class="rounded-circle image-cover"></a> <a
                                                                        href="/leh"
                                                                        class="float-left max-50 py-0 pl-3 text-capitalize">Leh</a>
                                                                </li>
                                                            </ul>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div class="border-0 gray-btn mb-3">
                                                    <div class="d-flex align-items-center flex-wrap"><a href="/azerbaijan"
                                                            class="text-capitalize text-truncate float-left text-dark pl-3">
                                                            Azerbaijan </a> </div>
                                                </div>
                                            </div>
                                            <div class="col-3 h-340">
                                                <div class="border-0 gray-btn mb-3">
                                                    <div class="d-flex align-items-center flex-wrap"><a href="/georgia"
                                                            class="text-capitalize text-truncate float-left text-dark pl-3">
                                                            Georgia </a> </div>
                                                </div>
                                                <div class="border-0 gray-btn mb-3">
                                                    <div class="d-flex align-items-center flex-wrap"><a href="/turkmenistan"
                                                            class="text-capitalize text-truncate float-left text-dark pl-3">
                                                            Turkmenistan </a> </div>
                                                </div>
                                                <div class="border-0 gray-btn mb-3">
                                                    <div class="d-flex align-items-center flex-wrap"><a href="/nepal"
                                                            class="text-capitalize text-truncate float-left text-dark pl-3">
                                                            Nepal </a> </div>
                                                </div>
                                                <div class="border-0 gray-btn mb-3">
                                                    <div class="d-flex align-items-center flex-wrap"><a href="/iran"
                                                            class="text-capitalize text-truncate float-left text-dark pl-3">
                                                            Iran </a> </div>
                                                </div>
                                            </div>
                                            <div class="col-3 h-340">
                                                <div class="border-0 gray-btn mb-3">
                                                    <div class="d-flex align-items-center flex-wrap"><a href="/siberia"
                                                            class="text-capitalize text-truncate float-left text-dark pl-3">
                                                            Siberia </a> <button block="" href="#"
                                                            class="no-focus position-relative ml-auto border-0 bg-transparent collapsed"
                                                            aria-expanded="false" aria-controls="destination2_12"
                                                            style="overflow-anchor: none;"><img
                                                                src="../assets/images/svgs/arrow-dark-gray.svg"
                                                                alt="Arrow"></button></div>
                                                    <div id="destination4_12" class="collapse" role="tabpanel"
                                                        style="display: none;">
                                                        <div class="accordion-body">
                                                            <ul class="list-unstyled list-countries pl-3 pt-2">
                                                                <li class="clearfix d-flex flex-wrap align-items-center"><a
                                                                        href="/siberia" class="float-left"><img
                                                                            src="https://indyguide-web-development.s3.us-east-2.amazonaws.com/destinations/1609714915_country_icon.jpg"
                                                                            alt="country-image"
                                                                            class="rounded-circle image-cover"></a> <a
                                                                        href="/siberia"
                                                                        class="float-left max-50 py-0 pl-3 text-capitalize">Siberia</a>
                                                                </li>
                                                                <li class="clearfix d-flex flex-wrap align-items-center"><a
                                                                        href="/murmansk" class="float-left"><img
                                                                            src="https://indyguide-web-development.s3.us-east-2.amazonaws.com/destinations/1609716495_country_icon.jpg"
                                                                            alt="country-image"
                                                                            class="rounded-circle image-cover"></a> <a
                                                                        href="/murmansk"
                                                                        class="float-left max-50 py-0 pl-3 text-capitalize">Murmansk</a>
                                                                </li>
                                                            </ul>
                                                        </div>
                                                    </div>
                                                </div>
                                                <div class="border-0 gray-btn mb-3">
                                                    <div class="d-flex align-items-center flex-wrap"><a href="/armenia"
                                                            class="text-capitalize text-truncate float-left text-dark pl-3">
                                                            Armenia </a> </div>
                                                </div>
                                                <div class="border-0 gray-btn mb-3">
                                                    <div class="d-flex align-items-center flex-wrap"><a href="/bhutan"
                                                            class="text-capitalize text-truncate float-left text-dark pl-3">
                                                            Bhutan </a> </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </ul>
                        </div>
                    </li>
                    <li><a href="/listing/all"> Listings</a></li>
                    <li><a href="/questions"> Forum</a></li>
                    <li><a href="/articles"> Blog</a></li>
                </ul>
                <ul class="list-unstyled d-flex flex-wrap align-items-center ml-lg-auto ml-md-auto ml-sm-auto mb-0">
                    <li class="d-lg-block d-md-block d-sm-block d-none"><a href="/host/signup" class="text-uppercase">apply
                            as host</a></li>
                    <li class="d-lg-block d-md-block d-sm-block d-none"><a href="/traveler/signup"
                            class="text-uppercase btn btn-primary border-30 px-3">sign up as traveler</a></li>
                    <li class="d-lg-block d-md-block d-sm-block d-none"><a href="/login" class="user"><img
                                src="../assets/images/user.png" alt="User-Image3"></a></li>
                </ul>
            </div>
        </nav>
    </div>
</template>


<style scoped>
@import "../assets/scss/components/_nav.scss";
@import "../assets/scss/style.scss";
</style>
<script setup>
const scrolled = ref(false);
const showDropdown = ref(false);

const handleScroll = () => {
    scrolled.value = window.scrollY > 0;
};

const toggleDropdown = () => {
    showDropdown.value = !showDropdown.value;
};

onMounted(() => {
    window.addEventListener('scroll', handleScroll);
});

onBeforeUnmount(() => {
    window.removeEventListener('scroll', handleScroll);
});
</script>

