# 3 Column preview card component

The coding challenege was hosted by [Frontendmentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-)

## Table of Contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Usage](#Usage/Examples)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

-[Desktop view](images/Desktopview.png)

-[Mobileview view](images/Mobileview.png)

### links

- Solution Url: [Solution](https://github.com/amishverma/3-column-preview-card-component)
- Live Site Url: [Live Site]()

## My process

### Built with

- HTML5 markup
- Sass
- Flexbox
- Media Queries

### What I learned

- Mainly I took this challenge to review the things that I have learned in Sass and to get better at responvsive design as well as using Sass
- I got to learn where to use the max-width and min-widht properties of css

## Usage/Examples

```css
.container {
  margin: 5% auto;

  width: 50%;
  min-width: 980px;
  height: 65vh;
  display: flex;
  justify-content: center;
  align-items: flex-start;

  & .column-1,
  .column-2,
  .column-3 {
    width: 50%;
    height: inherit;
  }
}
```

## Author

- FrontendMentor [Amish Verma](https://www.frontendmentor.io/profile/amishverma)
- Instagram [amish_verma](https://www.instagram.com/amish_verma/)
