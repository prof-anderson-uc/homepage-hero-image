# Hero Image Banner Example

This project demonstrates how to build a simple **hero image banner** for a webpage using HTML and CSS.

A hero image is a large photo, illustration, video, or banner placed near the top of a webpage. It is designed to catch the visitor’s attention, create a strong first impression, and help guide people toward important content.

## What this example includes

This page includes:

- a header with a site title and navigation links
- a hero image section near the top of the page
- text placed on top of the hero image
- a link styled to look like a button
- body content below the hero section
- a footer
- a small media query for basic responsive adjustments

## Files in this project

- `index.html` – the HTML structure for the page
- `hero.css` – the CSS styles for the page
- `reset.css` – a reset stylesheet to remove browser default spacing and styling
- `images/` – folder for image files used in the project

## How the hero section works

The hero section uses a background image in CSS instead of an `<img>` tag in the HTML.

Inside the hero section is a `<div>` with the class `hero-content`. This inner container holds the heading, paragraph, and link. The outer `.hero` section controls the background image, size, spacing, and alignment. The inner `.hero-content` controls the width and placement of the text.

The background image also includes a **dark transparent gradient layer** placed on top of the image. This helps the white text remain easier to read.

## Important CSS ideas used in this project

This example gives practice with several useful CSS concepts:

- **Flexbox** – used to align items in the header and to center the hero content
- **Background images** – used to place a large image behind the hero text
- **Background size: cover** – makes the image fill the hero area
- **Background position: center** – keeps the image centered
- **Padding** – adds space inside elements
- **Max-width** – prevents lines of text from becoming too wide
- **Hover styles** – changes the button color when the mouse is over it
- **Media query** – adjusts the layout and text sizes on smaller screens

## Customizing this example

After following along with the coding exercise, your version should not remain an exact copy of the starter.

You should customize your page by changing things such as:

- the hero image
- the heading text
- the paragraph text
- the button text
- colors
- text sizes
- button styling
- spacing
- gradient transparency

## Image tip

Hero images work best when they are **wide horizontal images** and fairly large.  
A good starting point is an image that is around **1200 pixels wide or more**.

If the image is too small, it may look blurry or pixelated when stretched across the hero area.

## Using this in your final project

You are welcome to reuse this code in your final project if it fits your site well. However, you should customize it enough that the final result clearly feels like your own work and not just an exact copy of the example.

## Learning goal

The goal of this exercise is to help you practice building a strong visual section near the top of a webpage and to think about how design can help guide a visitor’s attention.
