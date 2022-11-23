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
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./images/Frontend%20Mentor%20Stats%20preview%20card%20component-desktop.png)


### Links

- Solution URL: [Github Repo](https://github.com/ikennarichard/stats-preview-card)
- Live Site URL: [Live Site](https://ikennarichard.github.io/stats-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

- **mix-blend-mode**: This css property allows you to specify how an element blends with its direct parentbackground.

- **section**: HTML _section_ should always have a heading h2 - h6 in it. 

```css
.hero-image {
    background-color: hsl(277, 64%, 61%);
    border-radius: 0.3em 0.3em 0 0;
}

img {
    max-width: 100%; 
    mix-blend-mode: multiply;
    opacity: 90%;
    border-bottom: 1px solid var(--dark-desaturated-blue);
}
```


### Useful resources

- [w3schools](https://www.w3schools.com/cssref/pr_mix-blend-mode.php) - This guide was very helpful, it explains the property thoroughly and provides useful examples to help you understand.


## Author

- Website - [ikennarichard](https://www.github.com/ikennarichard)
- Frontend Mentor - [@ikennarichard](https://www.frontendmentor.io/profile/yourusername)


## Acknowledgments

Ill like to thank Front End Mentor for all the good it has brought to my development through these projects.
