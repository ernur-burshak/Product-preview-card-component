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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/image-product-desktop.jpg)

### Links

- Solution URL: [Add solution URL here](https://github.com/ernur-burshak/Product-preview-card-component)
- Live Site URL: [live site URL here](https://ernur-burshak.github.io/Product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS relative sizes of the rem unit
- Mobile-first workflow

### What I learned

I started creating adaptive layouts in this project and for the first time in my project I used the relative sizes of the same rem and I started my project with mobile adaptation then a computer.

```css
/* CSS Reset */
/* 1. Use a more-intuitive box-sizing model */
*,
*::before,
*::after {
  box-sizing: border-box;
}

/* 2. Remove default margin */
* {
  margin: 0;
}
```

```css
@media (min-width: 48rem) {
  .container {
    width: 37.5rem;
    height: auto;
    display: flex;
    flex-direction: row;
  }

  .image {
    width: 100%;
    height: auto;
    background-image: url("../images/image-product-desktop.jpg");
    border-top-left-radius: 10px;
    border-bottom-left-radius: 10px;
    border-top-right-radius: 0px;
  }

  .description {
    padding: 1.875rem;
    background-color: #ffffff;
    border-bottom-left-radius: 0px;
    border-bottom-right-radius: 10px;
    border-top-right-radius: 10px;
  }

  .add-to-cart:hover {
    background-color: #1a4032;
    cursor: pointer;
  }
}
```

### Continued development

In the future, I want to create larger and more optimized websites.

### Useful resources

- [resource 1](https://chatgpt.com/) - Helps with writing code.
- [resource 2](https://www.frontendmentor.io/) - It always helps to find good practice to improve the skills of the Front-end.

## Author

- Website - [Ernur](https://ernur-burshak.github.io/Product-preview-card-component/)
- Frontend Mentor - [@ernur-burshak](https://www.frontendmentor.io/profile/ernur-burshak)
- Linkedin - [Ernur Burshak](https://www.linkedin.com/in/ernur-burshak-7b6b0b31b?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)

## Acknowledgments

I always turn to the Frontend Mentor platform, it helps me improve my experience.
