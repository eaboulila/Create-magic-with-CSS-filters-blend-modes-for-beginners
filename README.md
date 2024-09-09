# Create Magic with CSS – Filters & Blend Modes for Beginners

This repository contains the project files from the **Create Magic with CSS – Filters & Blend Modes for Beginners** course. In this project, we use CSS to create visually engaging designs through filters, blend modes, and creative layout techniques.

## Project Overview

This exercise demonstrates how to use duotone effects in a web page layout. The project features a simple yet effective design for a city tour booking page. It combines text, images, and unique CSS techniques to create a dynamic, modern web design.

### HTML Structure

The HTML structure is minimal, focusing on clean, semantic markup. It includes:
- **Two main sections**: one for an image and one for product description.
- **Headings, paragraphs, and lists** to display details about the city tour.
- **Links to external resources** for images and credits.

### CSS Styling

The CSS makes extensive use of layout and visual effects, including:
- **Box-sizing** and layout control using `flex` and `inline-block`.
- **Custom fonts** from Google Fonts for a modern aesthetic.
- **Duotone image effect** created using borders and positioning.
- **Responsive design** with relative positioning and fluid layouts.
- **Unique colors** like coral red for buttons and soft blue borders to create contrast.
  
Key features include:
- A **large image section** with a bordered city image.
- A **product description section** that lists key features and pricing.
- A prominent **call-to-action button** designed with vibrant colors and bold fonts.

## HTML Code Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="styles/styles.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Karla:400,700" rel="stylesheet">
    <title>Elsayed Aboulila – duotone exercise</title>
</head>
<body>
    <section class="left-image">
        <img src="images/city.jpg" alt="City">
    </section>
    <section class="product-description">
        <h1 class="main">the city tour</h1>
        <h2>$599<br>unique city tour</h2>
        <p>Church-key selvage kitsch wayfarers, semiotics vinyl subway tile echo park celiac 90's. Fap cliche fam migas.<a href="http://theawwwesomes.org" target="_blank"><br>Created by The Awwwesomes</a>, Pics by <a href="http://unsplash.com" target="_blank">Unsplash</a><br></p>
        <ul>
            <li>Poke waistcoat mustache portland</li>
            <li>Drinking vinegar</li>
            <li>Chambray 8-bit</li>
            <li>Enamel pin</li>
        </ul>
        <div class="btn">buy ticket</div>
    </section>
</body>
</html>
```

## CSS Code Example

```css
*, *::before, *::after {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: 'Karla', sans-serif;
  position: relative;
}

p, ul, a {
  line-height: 150%;
  color: #3C3A47;
}

h1.main {
    font-size: 100px;
    margin: 0;
}

.left-image, .product-description {
  width: 50%;
  height: 100vh;
  float: left;
  display: inline-block;
  position: relative;
}

.left-image {
  border: 20px solid #3A6EA5;
  overflow: hidden;
}

.left-image img {
  position: absolute;
  width: 150%;
  bottom: 0;
}

.product-description {
  padding: 50px;
}

.product-description h2 {
  font-size: 30px;
  margin-bottom: 50px;
}

.btn {
    position: absolute;
    width: 100%;
    background: #FF6B6B;
    padding: 30px;
    bottom: 0;
    left: 0;
    color: #fff;
    text-align: center;
    font-size: 30px;
    font-weight: bold;
    letter-spacing: 2px;
}
```

## How to Use

1. Clone or download this repository.
2. Open the HTML file in any browser to view the layout.
3. Modify the images or content as needed for your project.
4. Use this example to practice CSS filters, blend modes, and other modern web design techniques.
