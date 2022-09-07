# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

./Screenshot Product-Preview-Card-solution.png

### Links

- Solution URL: https://github.com/Marchino5791/Frontend-Mentor-Product-Preview-Card-Solution-by-Marco-Paolino

## My process

### Built with

- HTML
- CSS

### What I learned

I learned to center verticaly a div using position and to use properly display function.

2 exemples:

1)

/* ---------- Div ---------- */
.main {
  width: 576px;
  display: flex;
  position: absolute;
  top: calc(50% - 216px);
  left: calc(50% - 288px);
}

2)

/* ---------- Image ---------- */
.image-product-desktop {
  display: block;
}

.image-product-mobile {
  display: none;
}

/* -------------------- Mobile version -------------------- */
@media (max-width: 600px) {
  .main {
    display: block;
  }
  
  .image-product-desktop {
    display: none;
  }

  .image-product-mobile {
    display: block;
  }
}

### Continued development

I'm going to focusing on creating more complex, flexible and responsive layout.

## Author

- Frontend Mentor - [@Marchino5791](https://www.frontendmentor.io/profile/Marchino5791)
