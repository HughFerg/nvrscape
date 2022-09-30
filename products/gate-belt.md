---
layout: default
title: Gate Belt
permalink: /gate-belt/
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
    width: 20em;
    height: auto;
}

.product-row {
    padding: 2em 2em 4em 2em;
    justify-content: center;
    align-items: center;
}

@media only screen and (min-device-width: 768px){
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

    .product-container {
        padding-top: 3em;
    }
}

.product-img {
    /* height: 28%; */
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
    font-size: .6em;
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
        <a class="nav-link" href="{{ site.baseurl }}/">home</a>
        <a class="nav-link active" href="{{ site.baseurl }}/shop">shop</a>
        <a class="nav-link" href="{{ site.baseurl }}/gallery">gallery</a>
        <a class="nav-link" href="{{ site.baseurl }}/faq">faq</a>
    </div>
</div>
<div class="product-container">
<div id='product-component-1664556237457'></div>
<script type="text/javascript">
/*<![CDATA[*/
(function () {
  var scriptURL = 'https://sdks.shopifycdn.com/buy-button/latest/buy-button-storefront.min.js';
  if (window.ShopifyBuy) {
    if (window.ShopifyBuy.UI) {
      ShopifyBuyInit();
    } else {
      loadScript();
    }
  } else {
    loadScript();
  }
  function loadScript() {
    var script = document.createElement('script');
    script.async = true;
    script.src = scriptURL;
    (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(script);
    script.onload = ShopifyBuyInit;
  }
  function ShopifyBuyInit() {
    var client = ShopifyBuy.buildClient({
      domain: 'nvrscape.myshopify.com',
      storefrontAccessToken: '2163d5c494928e7d00b569736352d75e',
    });
    ShopifyBuy.UI.onReady(client).then(function (ui) {
      ui.createComponent('product', {
        id: '7790754398454',
        node: document.getElementById('product-component-1664556237457'),
        moneyFormat: '%24%7B%7Bamount%7D%7D',
        options: {
  "product": {
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "100%",
          "margin-left": "0",
          "margin-bottom": "50px"
        },
        "text-align": "left"
      },
      "title": {
        "font-size": "26px"
      },
      "button": {
        "font-family": "Lato, sans-serif",
        ":hover": {
          "background-color": "#181414"
        },
        "background-color": "#0e0c0c",
        ":focus": {
          "background-color": "#181414"
        },
        "border-radius": "0px",
        "padding-left": "138px",
        "padding-right": "138px"
      },
      "price": {
        "font-size": "18px"
      },
      "compareAt": {
        "font-size": "15.299999999999999px"
      },
      "unitPrice": {
        "font-size": "15.299999999999999px"
      }
    },
    "layout": "horizontal",
    "contents": {
      "img": false,
      "imgWithCarousel": true,
      "description": true
    },
    "width": "100%",
    "text": {
      "button": "Add to cart"
    },
    "googleFonts": [
      "Lato"
    ]
  },
  "productSet": {
    "styles": {
      "products": {
        "@media (min-width: 601px)": {
          "margin-left": "-20px"
        }
      }
    }
  },
  "modalProduct": {
    "contents": {
      "img": false,
      "imgWithCarousel": true,
      "button": false,
      "buttonWithQuantity": true
    },
    "styles": {
      "product": {
        "@media (min-width: 601px)": {
          "max-width": "100%",
          "margin-left": "0px",
          "margin-bottom": "0px"
        }
      },
      "button": {
        "font-family": "Lato, sans-serif",
        ":hover": {
          "background-color": "#181414"
        },
        "background-color": "#0e0c0c",
        ":focus": {
          "background-color": "#181414"
        },
        "border-radius": "0px",
        "padding-left": "138px",
        "padding-right": "138px"
      },
      "title": {
        "font-family": "Helvetica Neue, sans-serif",
        "font-weight": "bold",
        "font-size": "26px",
        "color": "#4c4c4c"
      },
      "price": {
        "font-family": "Helvetica Neue, sans-serif",
        "font-weight": "normal",
        "font-size": "18px",
        "color": "#4c4c4c"
      },
      "compareAt": {
        "font-family": "Helvetica Neue, sans-serif",
        "font-weight": "normal",
        "font-size": "15.299999999999999px",
        "color": "#4c4c4c"
      },
      "unitPrice": {
        "font-family": "Helvetica Neue, sans-serif",
        "font-weight": "normal",
        "font-size": "15.299999999999999px",
        "color": "#4c4c4c"
      }
    },
    "googleFonts": [
      "Lato"
    ],
    "text": {
      "button": "Add to cart"
    }
  },
  "option": {},
  "cart": {
    "styles": {
      "button": {
        "font-family": "Lato, sans-serif",
        ":hover": {
          "background-color": "#181414"
        },
        "background-color": "#0e0c0c",
        ":focus": {
          "background-color": "#181414"
        },
        "border-radius": "0px"
      }
    },
    "text": {
      "total": "Subtotal",
      "button": "Checkout"
    },
    "popup": false,
    "googleFonts": [
      "Lato"
    ]
  },
  "toggle": {
    "styles": {
      "toggle": {
        "font-family": "Lato, sans-serif",
        "background-color": "#0e0c0c",
        ":hover": {
          "background-color": "#181414"
        },
        ":focus": {
          "background-color": "#181414"
        }
      }
    },
    "googleFonts": [
      "Lato"
    ]
  }
},
      });
    });
  }
})();
/*]]>*/
</script>

<div class="footer">
copyright © 2022 nvrscape
</div>