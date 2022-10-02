---
layout: default
title: shop
permalink: /shop/
---
<style>

a {
    text-decoration: none;
}

img {
    max-width: 100%;
}

.content-container {
    position: relative;
    /* display: flex; */
    /* min-height: 100vh; */
}

.nav-container {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    row-gap: 0;
}

.nav-link {
    padding: 0 1em 1em 0;
    color: #000000;
}

.active {
    font-weight: bold;
    text-decoration: underline;
}

.header-img {
    width: 20em;
    height: auto;
}

.product-row {
    padding: 0em 2em 4em 2em;
    justify-content: center;
    align-items: center;
}

@media only screen and (min-device-width: 768px){

    .content-container {
        height: 60em;
    }

    .header-img {
        width: 30em;
        height: auto;
    }
    .product-row {
        display: flex;
        padding: 2em 1em 4em 1em;
        justify-content: center;
        align-items: center;
        width: 100%;
    }

    .product-img {
        /* height: 28%; */
    }
}

.product-img {
    /* height: 28%; */
}

.product-img-link {

}

.footer {
    position: absolute;
    bottom:0;
    left:0;
    width:100%;
    /* height: 3em; */
    text-align: center;
    align-items: center;
        /* margin-top: auto; */
}

</style>
<!-- nav links -->
<div class="content-container">
<div class="nav-container">
    <!-- gif header -->
    <div class="header-logo">
        <video class="header-img" autoplay loop muted>
            <source src="../images/rotating-logo.mp4" type="video/mp4">
            <!-- webp here? -->
            Your browser does not support the video tag.
        </video> 
    </div>
    <div class="nav-links">
        <a class="nav-link" href="{{ site.baseurl }}/">home</a>
        <a class="nav-link active" href="{{ site.baseurl }}/shop">shop</a>
        <a class="nav-link" href="{{ site.baseurl }}/gallery">gallery</a>
        <a class="nav-link" href="{{ site.baseurl }}/faq">faq</a>
    </div>
</div>

<!-- product row -->
<div class="product-row">
    <a class="product-img-link" href="{{ site.baseurl }}/gate-belt">
        <img class="product-img" src="../images/products/belt-shot1.png">
    </a>
    <a class="product-img-link" href="{{ site.baseurl }}/transcendance-tee">
        <img class="product-img" src="../images/products/angel-tee1.png">
    </a>
    <a class="product-img-link" href="{{ site.baseurl }}/spiral-tee">
        <img class="product-img" src="../images/products/spiral-tee.png">
    </a>
    <a class="product-img-link" href="{{ site.baseurl }}/compass-bandanna">
        <img class="product-img" src="../images/products/bandana1.png">
    </a>
</div>

<div class="footer">
<a href="https://www.instagram.com/nvrscape/">
    <i class="fa-brands fa-square-instagram fa-xl"></i>
</a>
<a href="https://twitter.com/nvrscape">
    <i class="fa-brands fa-square-twitter fa-xl"></i>
</a>
<br>
<br>
<div style="font-size: .6em">
copyright © 2022 nvrscape
</div>
</div>
</div>