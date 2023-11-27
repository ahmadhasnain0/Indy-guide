<template>
    <section class="banner-section position-relative">
        <div class="video position-relative w-100 os">
            <div class="video-title-overlay position-absolute text-white">
                <p class="text-center font-20 mb-2">Most-trusted Travel Platform for</p>
                <h1 class="text-center font-weight-bold text-capitalize">Local Guides &amp; Tours in Central
                    Asia</h1>
            </div>
            <div class="video-wrapper d-lg-block d-md-block d-none h-100vh">
                <div class="gradient-bg position-absolute w-100 h-100vh"></div>
                <div class="primary-gradient position-absolute w-100 h-100vh"></div>
                <div class="overlay position-absolute w-100 h-100vh"></div>
                <video autoplay="autoplay" muted="muted" loop="loop" class="psoition-lg-absolute position-static"
                    __idm_id__="1253377">
                    <source src="../assets/video/INDY GUIDE - Experiences in Underrated Destinations.mp4" type="video/mp4" >
                </video>
            </div>
        </div> <span class="d-lg-inline d-md-inline d-block"></span>
        <div class="search-destination position-absolute">
            <form>
                <div class="row m-0">
                    <div class="px-2 col-sm-6 col-md-6 col-lg">
                        <div class="form-group mb-0  ">
                            <div>
                                <select name="Destination" id="Destination " class="select">
  <option class="option" value="">Selec Destination</option>
  <option class="option"  value="United Kindom">United Kindom</option>
  <option class="option"  value="Canada">Canada</option>
  <option class="option"  value="Afganistan">Afganistan</option>
</select>
                            </div>
                        </div>
                    </div>
                    <div class="px-2 col-sm-6 col-md-6 col-lg">
                        <div class="form-group mb-0  ">
                            <div>
                                <select name="Destination" id="Destination " class="select">
  <option class="option" value="">Tours & activities</option>
  <option class="option" value="saab">Saab</option>
  <option class="option" value="mercedes">Mercedes</option>
  <option class="option" value="audi">Audi</option>
</select>
                            </div>
                        </div>
                    </div>
                    <div class="px-2 mt-lg-0 mt-4 mx-lg-0 mx-auto col-sm-6 col-md-6 col-lg"><button
                            class="btn btn-primary border-30 w-100 text-white">Search</button></div>
                </div>
            </form>
        </div>
        <div class="usp-wrapper w-100 clearfix d-lg-block d-flex">
            <div class="usp-single-cover float-left text-center position-relative">
                <div class="usp-icon"><img src="../assets/images/svgs/verified-yellow.svg" alt="Verified Hosts"
                        class="image-contain w-100 h-100"></div>
                <div class="usp-detail">
                    <h4 class="mb-0 text-capitalize text-break">verified <span
                            class="d-lg-inline d-md-inline d-block">hosts</span></h4>
                </div>
            </div>
            <div class="usp-single-cover float-left text-center position-relative">
                <div class="usp-icon"><img src="../assets/images/svgs/selection-yellow.svg" alt="Verified Hosts"
                        class="image-contain w-100 h-100"></div>
                <div class="usp-detail">
                    <h4 class="mb-0 text-capitalize text-break"> Largest <span
                            class="d-lg-inline d-md-inline d-block">Selection</span></h4>
                </div>
            </div>
            <div class="usp-single-cover float-left text-center position-relative">
                <div class="usp-icon"><img src="../assets/images/svgs/trips-yellow.svg" alt="Verified Hosts"
                        class="image-contain w-100 h-100"></div>
                <div class="usp-detail">
                    <h4 class="mb-0 text-capitalize text-break">Customized <span
                            class="d-lg-inline d-md-inline d-block">Trips</span></h4>
                </div>
            </div>
            <div class="usp-single-cover float-left text-center position-relative">
            <div class="usp-icon"><img src="../assets/images/svgs/tips-yellow.svg" alt="Verified Hosts"
                    class="image-contain w-100 h-100"></div>
            <div class="usp-detail">
                <h4 class="mb-0 text-capitalize text-break">Insider <span
                        class="d-lg-inline d-md-inline d-block">Tips</span></h4>
            </div>
        </div>
    </div>
</section></template>

<style scoped>
@import "../assets/scss/components/_header.scss";
@import "../assets/scss/style.scss";
</style>