---
layout: default
title: collections
permalink: /collections/all/
---
<style>
@media only screen and (min-device-width: 768px) {
    .footer {
        position: absolute;
    }
}
    .glitch:hover {
        animation: glitch 1s linear infinite;
    }

    @keyframes glitch {

        2%,
        64% {
            transform: translate(2px, 0) skew(0deg);
        }

        4%,
        60% {
            transform: translate(-2px, 0) skew(0deg);
        }

        62% {
            transform: translate(0, 0) skew(5deg);
        }
    }

    .glitch:before,
    .glitch:after {
        content: attr(title);
        position: absolute;
        left: 0;
    }

    .glitch:before {
        animation: glitchTop 1s linear infinite;
        clip-path: polygon(0 0, 100% 0, 100% 33%, 0 33%);
        -webkit-clip-path: polygon(0 0, 100% 0, 100% 33%, 0 33%);
    }

    @keyframes glitchTop {

        2%,
        64% {
            transform: translate(2px, -2px);
        }

        4%,
        60% {
            transform: translate(-2px, 2px);
        }

        62% {
            transform: translate(13px, -1px) skew(-13deg);
        }
    }

    .glitch:after {
        animation: glitchBotom 1.5s linear infinite;
        clip-path: polygon(0 67%, 100% 67%, 100% 100%, 0 100%);
        -webkit-clip-path: polygon(0 67%, 100% 67%, 100% 100%, 0 100%);
    }

    @keyframes glitchBotom {

        2%,
        64% {
            transform: translate(-2px, 0);
        }

        4%,
        60% {
            transform: translate(-2px, 0);
        }

        62% {
            transform: translate(-22px, 5px) skew(21deg);
        }
    }

    
</style>
<!-- nav links -->
<div class="content-container">
<div class="nav-container">
    <!-- gif header -->
    <div class="header-logo">
        <video class="header-img" autoplay loop muted playsinline defaultMuted>
            <source src="/images/rotating-logo.mp4" type="video/mp4">
            <!-- webp here? -->
            Your browser does not support the video tag.
        </video> 
    </div>
    <div class="nav-links">
        <a class="nav-link" href="{{ site.url }}/">home</a>
        <a class="nav-link active" href="{{ site.url }}/collections/all/">collections</a>
        <a class="nav-link" href="/media">media</a>
        <a class="nav-link" href="{{ site.url }}/faq">faq</a>
    </div>
</div>

<!-- product row -->
<div class="product-row">
    <a class="product-img-link glitch" href="{{ site.url }}/gate-belt">
        <img class="product-img js-vhs-filter" src="/images/products/belt-shot1.png">
    </a>
    <a class="product-img-link glitch" href="{{ site.url }}/transcendance-tee">
        <img class="product-img" src="/images/products/angel-tee1.png">
    </a>
    <a class="product-img-link glitch" href="{{ site.url }}/spiral-tee">
        <img class="product-img" src="/images/products/spiral-tee.png">
    </a>
    <a class="product-img-link glitch" href="{{ site.url }}/compass-bandanna">
        <img class="product-img" src="/images/products/bandana1.png">
    </a>
</div>

</div>