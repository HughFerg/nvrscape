---
layout: default
title: faq
permalink: /faq/
---
<style>

a {
    text-decoration: none;
}

img {
    max-width: 100%;
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
    width: 30em;
    height: auto;
}

.product-row {
  display: flex;
  padding: 2em 0 4em 0;
  justify-content: center;
    align-items: center;
  width: 100%;
}

.product-img {
    height: 28%;
    /* align-items: center; */
}

.product-img-link {

}

.footer {
    position:fixed;
    bottom:0;
    left:0;
    width:100%;
    text-align: center;
    padding-bottom: 1em;
}

</style>
<!-- nav links -->
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
        <a class="nav-link" href="{{ site.baseurl }}">home</a>
        <a class="nav-link" href="{{ site.baseurl }}/shop">shop</a>
        <a class="nav-link" href="{{ site.baseurl }}/gallery">gallery</a>
        <a class="nav-link active" href="{{ site.baseurl }}/faq">faq</a>
    </div>
</div>

<!-- product row -->
<div class="product-row">
    <a class="product-img-link" href="./">
        <img class="product-img" src="../images/products/angel-tee1.png">
    </a>
    <a class="product-img-link">
        <img class="product-img" src="../images/products/staircase-tee.png">
    </a>
    <a class="product-img-link">
        <img class="product-img" src="../images/products/bandana1.png">
    </a>
    <a class="product-img-link">
        <img class="product-img" src="../images/products/belt-shot1.png">
    </a>
</div>

<div class="footer">
copyright © 2022 Nvrscape
</div>