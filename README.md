# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62).

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

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Flex
- CSS Grid
- Desktop-first workflow

### What I learned

- Center a `div` using CSS Flex.

```css
.center-screen {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
}
```

- Fill the image full of a `div`.

```css
.card-img img {
  display: block;
}
```

- Create an transparent overlay for an image.

```css
.card-img {
    position: relative;
  }

.card-img img {
  display: block;
}

.img-overlay {
  width: 100%;
  height: 100%;
  position: absolute;
  top: 0;
  left: 0;
  z-index: 10;
  background-color: hsla(277, 64%, 30%, 0.6);
}
```

### Continued development

- CSS position, especially the application of `relative` and `absolute`.
- And a lot more.

## Author

- Frontend Mentor - [@tttinh](https://www.frontendmentor.io/profile/tttinh)
