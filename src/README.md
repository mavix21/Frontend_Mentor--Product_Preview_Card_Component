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

![](./screenshot-desktop.jpg)
![](./screenshot-mobile.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- SASS
- BEM
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- ITCSS

### What I learned

For this project I wanted to use SASS because I love to keep my code organized and SASS allows me to do that. I know it's a little bit of an overkill, but I would like to get use to it since the very beginning.

I also wanted to implement the ITCSS architecture because I think it makes CSS code mode readible and maintainable. So you will see that I organized all my sass files inside the sass folder. For those who are not familiar with the ITCSS structure, I'm going to briefly explain what you can find inside each folder:

- [abstracts]: Basically all the content that will not render to actual CSS code, such as custom properties, functions, mixins, etc.

- [generic]: Reset and/or Normalize styles (I use both). This is the first layer that will generate actual CSS.

- [elements]: The basic styling for HTML elements (like H1, a, img). Think about how your site would look without classes.

- [objects]: This is the first layer where we include classes. This classes define undecorate desing pattern, for example, layout related classes. Think of this as more architectural code.

- [components]: This is where most of our work takes place. Here we will find the specific UI components.

### Continued development

I really want to dig more into SASS, so I will keep using it in my future projects.

### Useful resources

- [ITCSS Architecture](https://www.xfive.co/blog/itcss-scalable-maintainable-css-architecture/) - You can read more about ITCSS architecture here.

## Author

- Frontend Mentor - [@mavix21](https://www.frontendmentor.io/profile/mavix21)
