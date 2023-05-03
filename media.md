---
layout: default
title: media
permalink: /media/
---
<style>
.promo-video-container {
    display: flex;
    width: 100%;
    padding-top: 2em;
    padding-bottom: 50%;
    height: 0; 
    position: relative;
    text-align: center;
    justify-content: center;
}

.promo-video-container iframe{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    margin: 0 auto;
}

.gallery-container {
    /* display: flex;
    justify-content: center;
    align-items: center; */
}

.gallery-img-row {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-flow: column;
    /* max-height: 10em;  */
    /* margin: 0 auto; */
    /* position: relative;
    justify-content: center;
    align-items: center;
    margin: 0 auto; */
}

.gallery-img {
    max-width: 20em; 
    padding: 0;
    margin: 0 auto;
}

.footer {
    padding-top: 4em;
}

@media only screen and (min-device-width: 768px) {
    .promo-video-container {
        width: 100%;
        padding-top: 2em;
        padding-bottom: 46.25%;
        height: 0;
    }
    .promo-video-container iframe{
        /* width: 90%; */
    }
    .gallery-img {
        max-width: 40em; 
        padding: 1em;
        margin: 0 auto;
    }
</style>

<!-- nav links -->
<div class="nav-container" style="padding-bottom: 4em;">
    <!-- gif header -->
    <div class="header-logo">
        <!-- <video class="header-img" autoplay loop muted playsinline defaultMuted>
            <source src="../images/rotating-logo.mp4" type="video/mp4">
            webp here?
            Your browser does not support the video tag.
        </video>  -->
        <img class="header-img" src="/images/textLogo.png">
    </div>
    <div class="nav-links">
        <a class="nav-link" href="{{ site.url }}/">home</a>
        <a class="nav-link" href="{{ site.url }}/collections/all/">collections</a>
        <a class="nav-link active" href="{{ site.url }}/media">media</a>
        <a class="nav-link" href="{{ site.url }}/faq">faq</a>
    </div>
</div>

<div class="gallery-container">
    <div class="gallery-img-row">
        <div class="gallery-img"><img class="gallery-img" src="/images/wishs1.jpg"></div>
        <div class="gallery-img"><img class="gallery-img" src="/images/swank3.jpg"></div>
        <div class="gallery-img"><img class="gallery-img" src="/images/swank4.jpg"></div>
        <div class="gallery-img"><img class="gallery-img" src="/images/swank6.jpg"></div>
    </div>
    <div class="promo-video-container">
        <iframe allow='autoplay' width="560" height="315" src="https://www.youtube.com/embed/X-3k-pjilJ0?autoplay=1&mute=1&origin=https://nvrscape.com" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
</div>