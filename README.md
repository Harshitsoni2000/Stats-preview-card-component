# Frontend Mentor - Stats preview card component solution

  This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

  ![On Desktop](https://github.com/Harshitsoni2000/Stats-preview-card-component/blob/main/ss/ss-Desktop.PNG)
  ![On Mobile](https://github.com/Harshitsoni2000/Stats-preview-card-component/blob/main/ss/ss-mobile.PNG)

### Links

  - Solution URL: [Click to see Solution](https://github.com/Harshitsoni2000/Stats-preview-card-component)
  - Live Site URL: [Click to see live site](https://harshitsoni2000.github.io/Stats-preview-card-component/)

## My process

### Built with

  - Semantic HTML5 markup
  - CSS custom properties
  - Flexbox
  - CSS Grid
  - Mobile-first workflow

### What I learned

  1. How to use mix-blend-mode to make image and background-color blend-in with each other.
    ```html
    <div class="card card-image h-100">
      <img class="image active" src="images/image-header-mobile.jpg" alt="Team-candid">
    </div>
    ```
    ```css
    .card-image {
      background-color: hsl(277, 64%, 61%);
    }

    .image {
      mix-blend-mode: multiply;
    }
    ```

  2. How to use .no-gutters class to remove gutters from a row and its columns.
    ```html
    <div class="row no-gutters">
    ```

### Continued development

  I want to continue focusing on display attribute more. This is a concept that I'm still not completely comfortable with.

### Useful resources

  - [mix-blend-mode](https://www.w3schools.com/cssref/pr_mix-blend-mode.asp) - This helped me understand mix-blend-mode. I really liked this concept and will use it going forward.
  - [.no-gutters](https://getbootstrap.com/docs/4.6/components/card/#horizontal) - This is an amazing article which helped me finally understand .no-gutters class. I'd recommend it to anyone still learning this concept.

## Author

  - Frontend Mentor - [@Harshitsoni2000](https://www.frontendmentor.io/profile/@Harshitsoni2000)
  - GitHub - [@Harshitsoni2000](https://github.com/Harshitsoni2000)
