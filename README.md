# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Solution URL: https://github.com/Marchino5791/Frontend-Mentor-Product-Preview-Card-Solution-by-Marco-Paolino
- Live Site URL: https://marchino5791.github.io/Frontend-Mentor-Product-Preview-Card-Solution-by-Marco-Paolino

## My process

### Built with

- HTML
- CSS
- Mobile-first workflow

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

I have also learned about accessibility: ARIA label and role.

### Continued development

I'm going to focusing on creating more complex, flexible and responsive layout.

## Author

- Frontend Mentor - [@Marchino5791](https://www.frontendmentor.io/profile/Marchino5791)
- LinkedIn - [@Marco Antonio Paolino](https://www.linkedin.com/in/marco-paolino/)
