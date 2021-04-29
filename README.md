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
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Solution URL: [GitHub repository](https://github.com/AyulaBoyilo/FMstatsPreviewCard)
- Live Site URL: [GitHub Pages](https://ayulaboyilo.github.io/FMstatsPreviewCard)

## My process

### Built with

- Semantic HTML5 markup
- SCSS and CSS3
- Flexbox

### What I learned

The challenge served as a knowledge refresher of color overlay with pseudo elements and HTML picture tag.

```html
<picture>
  <source
    media="(min-width:700px)"
    srcset="./images/image-header-desktop.jpg"
  />
  <img src="./images/image-header-mobile.jpg" alt="business meeting" />
</picture>
```

```css
.wrap::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: $soft-violet;
  mix-blend-mode: multiply;
  z-index: 1;
}
```

### Useful resources

- [HTML picture Tag](https://www.w3schools.com/tags/tag_picture.asp) - w3schools HTML picture tag page.
- [Use CSS ::before and ::after for simple, spicy image overlays](https://bryanlrobinson.com/blog/how-to-css-after-elements-for-background-overlays/) - A nice article detailing the usage of background overlays.

## Author

- Ayula Boyilo
