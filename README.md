# Tolstoy Owl Carousel

Tolstoy Embed Combined with Owl Carousel

## Important Configuration

**Download Owl Carousel Files**

Download Link: [Owl Carousel Website](https://owlcarousel2.github.io/OwlCarousel2/)

**Import the Following Owl Carousel Files to the Asset Folder in Your Code Editor:**

1. `owl.carousel.min.css`
2. `owl.theme.default.min.css`
3. `owl.carousel.min.js`
4. `jquery.min.js`

**Initiate the Files in `theme.liquid` File:**

Add the following code in your `theme.liquid` file:

```html
<!-- Owl Carousel CSS (Place this before the </head> tag) -->
<link rel="stylesheet" href="{{ 'owl.carousel.min.css' | asset_url }}">
<link rel="stylesheet" href="{{ 'owl.theme.default.min.css' | asset_url }}">

<!-- Owl Carousel JS (Place this before the </body> tag) -->
<script src="{{ 'jquery.min.js' | asset_url }}" defer></script>
<script src="{{ 'owl.carousel.min.js' | asset_url }}" defer></script>
