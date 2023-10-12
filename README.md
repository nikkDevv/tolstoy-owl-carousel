# tolstoy-owl-carousel
TOLSTOY EMBED COMBINED WITH OWL CARUSEL

important! CONFIGURATION:

Download Owl Carousel file: 

download link: https://owlcarousel2.github.io/OwlCarousel2/

IMPORT the following OWL CAROUSEL FILES TO ASSET FOLDER IN EDIT CODE:

owl.carousel.min.css
owl.theme.default.min.css
owl.carousel.min.js
jquery.min.js


INITIATE THE FILES IN theme.liquid file:
<!-- Owl Carousel CSS --> before the </head> tag
<link rel="stylesheet" href="{{ 'owl.carousel.min.css' | asset_url }}">
<link rel="stylesheet" href="{{ 'owl.theme.default.min.css' | asset_url }}">

 <!-- Owl Carousel JS --> before the </body> tag
<script src="{{ 'jquery.min.js' | asset_url }}" defer></script>
<script src="{{ 'owl.carousel.min.js' | asset_url}}" defer></script>
