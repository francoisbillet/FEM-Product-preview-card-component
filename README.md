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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./images/Screenshot%202022-10-10%20at%2017-33-19%20Frontend%20Mentor%20Product%20preview%20card%20component.png)

### Links

Live Site URL: [https://product-preview-card-component-khaki.vercel.app/](https://product-preview-card-component-khaki.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Media queries

### What I learned

- Add a line through a word with CSS :

```css
.word {
  text-decoration: line-through;
}
```

- Create breakpoints with media queries for a (kind of) responsive design :

```css
@media (max-width: 1200px) {
  main.card {
    width: 50%;
  }
}
```

- Have 2 images defined in the HTML (one for mobile and one for desktop) and display one or the other with ```display: block``` or ```display: none``` depending on the device's width.

### Continued development

HTML :
- Is a ```<span>``` a proper way to display PERFUME ?
- Should I englobe "Add to Cart" into a tag (such as ```<span>``` ?)

CSS:
- I had a hard time managing the image's height and width and knowing when to use min-width (or height), width (or height) and max-width (or height).
- When the width of the device > 1500 px, the card's height increases and provokes the appearance of white space in the right panel. Do I have to set a fixed height to avoid this ?
- This is the first time I code something kinda responsive. Are there any good practices I should know ? I found it a little vague to indicate a few breakpoints here and there to modify the width of the card.
- Is having 2 html ```<img>``` and display/hide one in CSS depending on the device's width the right way to go ?
- Mobile first or Desktop first ?

### Useful resources

[Josh Comeau's CSS Reset](https://www.joshwcomeau.com/css/custom-css-reset/) - This helped me better understand CSS resets. I plan on using parts of his reset and modify it over time with my experience.

## Author

Frontend Mentor - [FunkyCreep](https://www.frontendmentor.io/profile/francoisbillet)