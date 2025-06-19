# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

![Solution](/images/solution-screenshot.png)

### Links

- Solution URL: [https://github.com/HaiDangN/3-column-preview-card-component](https://github.com/HaiDangN/3-column-preview-card-component)
- Live Site URL: [https://haidangn.github.io/3-column-preview-card-component/](https://haidangn.github.io/3-column-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learned how to absolutely position an element relative to its parent:
```css
.parent {
    position: relative;
}
.child {
    position: absolute;
    bottom: 3rem;
}
```

I'm continuing to get a better grasp of height, min-height, max-height and widths.

I learned the BEM naming convention which stands for Block, Element, and Modifier. It is a methodology that is used to make it easier to read css styling and give a standard naming convention to nested elements within components.

```html
    <section class="preview-card">
      <section class="preview-card__column preview-card__column--sedan">
        <img src="images/icon-sedans.svg" alt="Small illustration of sedan.">
        <h1>Sedans</h1>
        <p>
          Choose a sedan for its affordability and excellent fuel economy. Ideal for cruising in the city
          or on your next road trip.
        </p>
        <button class="preview-card__button--sedan">Learn More</button>
      </section>
```
