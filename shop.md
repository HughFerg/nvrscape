---
layout: default
title: shop
permalink: /shop/
---
<style>

a {
    text-decoration: none;
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
}

.header-img {
    width: 30em;
    height: auto;
}

.product-row {
  display: flex;
  padding: 4em;
  justify-content: center;
}

.product-img {
    width: 20em;
    height: auto;
}

.product-img-link {

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
        <a class="nav-link" href="./index.html">home</a>
        <a class="nav-link" href="./shop.html">shop</a>
        <a class="nav-link" href="./gallery.html">gallery</a>
        <a class="nav-link" href="./faq.html">faq</a>
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