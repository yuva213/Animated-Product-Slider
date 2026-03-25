# Animated Product Slider

## Overview
The **Animated Product Slider** is a visually appealing, interactive web component built with HTML, CSS, and vanilla JavaScript. It is designed to showcase multiple variations of a product—in this case, DualShock 4 Wireless Controllers in different colors—using a rotating carousel mechanism.

## Features
- **Interactive Carousel:** A smooth, rotating circular slider that displays product images. Both the slider container and individual product pictures rotate gracefully to maintain their upright orientations.
- **Dynamic Backgrounds:** The background color of the web page dynamically shifts to match the color theme of the currently active product variant.
- **Product Information Panel:** Corresponding details for the selected product are displayed, including name, price, description, and available colors.
- **Navigation Controls:** Next and previous buttons to intuitively browse through the sequence of products.
- **Responsive Animations:** Uses CSS transforms to animate elements dynamically.
- **Custom Icons:** Utilizes [Boxicons](https://boxicons.com/) to render simple, modern user interface icons.

## Technologies Used
- **HTML5:** Provides the semantic structure of the DOM elements.
- **CSS3:** For styling, custom properties (CSS variables), layout formatting (Flexbox/Grid), and animation (`transform` properties).
- **JavaScript (Vanilla):** Handles user interactions (button clicks), DOM manipulations, index tracking, and triggering UI updates.

## Project Structure
```text
Animated Product Slider/
│
├── images/            # Directory containing all product images (e.g., img1.png, img2.png)
├── index.html         # Main markup file containing the slider layout
├── style.css          # Styling file for layouts, typography, and visual adjustments
├── script.js          # Logic file containing Javascript for animation and interaction
└── README.md          # Project documentation (This file)
```

## How to Run
1. Clone or download this repository to your local machine.
2. Ensure you have the entire project folder intact, containing `index.html`, `style.css`, `script.js`, and the `images` folder.
3. Open the `index.html` file using any modern web browser.
    - *Alternatively, you can run the directory through a local development server like VS Code's "Live Server" extension for a better experience.*
4. Use the left and right navigation arrows to interact with the project and observe the animations!

## Customization
To use this slider for your own products:
1. **Set Images:** Replace the images inside the `images/` folder and adjust the `<img src="...">` tags in `index.html`.
2. **Update Details:** Edit the product details inside the `.info-item` elements within `index.html`.
3. **Themes:** In `script.js`, tweak the `colors` array to pair appropriately with your newly added images.

```javascript
// script.js - Background transitions
let colors = ['#3674be', '#d26181', '#ceb13d', '#c6414c', '#171f2b', '#50aa61']; // Adjust these hex codes
```
