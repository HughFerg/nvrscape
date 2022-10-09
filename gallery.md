---
layout: default
title: gallery
permalink: /gallery/
---
<style>
.promo-video-container {
    /* display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    padding: 2em; */
    position: relative;
    width: 100%;
    padding-top: 2em;
    padding-bottom: 56.25%;
    height: 0;
}
.promo-video-container iframe{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}

@media only screen and (min-device-width: 768px) {
    .footer {
        /* position: absolute; */
    }
}
</style>
<!-- nav links -->
<div class="nav-container">
    <!-- gif header -->
    <div class="header-logo">
        <video class="header-img" autoplay loop muted playsinline defaultMuted>
            <source src="../images/rotating-logo.mp4" type="video/mp4">
            <!-- webp here? -->
            Your browser does not support the video tag.
        </video> 
    </div>
    <div class="nav-links">
        <a class="nav-link" href="{{ site.url }}/">home</a>
        <a class="nav-link" href="{{ site.url }}/collections/all/">collections</a>
        <a class="nav-link active" href="{{ site.url }}/gallery">gallery</a>
        <a class="nav-link" href="{{ site.url }}/faq">faq</a>
    </div>
</div>

<div class="promo-video-container">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/X-3k-pjilJ0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>