# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62).

## Table of contents
- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview
### The challenge
Users should be able to:
- View the optimal layout depending on their device's screen size

### Screenshot
![Desktopview](./design/desktop-preview.jpg)

## My process
### Built with
- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned
I was able to learn how to use the image filter property as well as applying an image as a background to an HTML element. 

```html
<div class="imageWrapper"></div>
```
```css
.imageWrapper{
		background: url(./images/image-header-mobile.jpg);
		filter: opacity(0.5) drop-shadow(0 0 hsl(277, 64%, 61%));
		background-repeat: no-repeat;
		background-size: contain;
		width: 16rem;
		display: block;
		margin-left: auto;
		margin-right: auto;
	}
```

### Continued development
I will be doing further research on CSS image properities.

### Useful resources

- [Example resource 1](https://www.fonts.google.com) - This helped me to access different kind of fonts.It makes your web more beautiful also adding a great typography.
- [Example resource 2](https://www.w3schools.com) - This is an amazing website to learn coding and it is absolutely beginnner friendly.

## Author
- Website - [minimilliano](https://github.com/minimilliano)
- Frontend Mentor - [@minimilliano](https://www.frontendmentor.io/profile/minimilliano)
