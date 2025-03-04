# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![screenshot preview](./images/desktop-preview.jpg)

### Links

- Solution URL: [GitHub Repo](https://github.com/MATBMS/nft-preview-card-component)
- Live Site URL: [GitHub Page](https://matbms.github.io/nft-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I have learned to add several layers on a image background.

```css
.product-img:hover {
  background-image: url("./images/image-equilibrium.jpg"), linear-gradient(
      rgba(0, 255, 248, 0.5),
      rgba(0, 255, 248, 0.5)
    ), url("./images/icon-view.svg");
  background-size: cover, cover, 48px;
  background-position: center, center, center;
  background-repeat: no-repeat, no-repeat, no-repeat;
  background-blend-mode: overlay, overlay, normal;
}
```
