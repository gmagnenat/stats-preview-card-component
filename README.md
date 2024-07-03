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
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [https://www.frontendmentor.io/solutions/stats-preview-card-component-scss-bem-vite-3Lc8cgJFLP](https://www.frontendmentor.io/solutions/stats-preview-card-component-scss-bem-vite-3Lc8cgJFLP)
- Live Site URL: [https://nimble-pony-2286e3.netlify.app/](https://nimble-pony-2286e3.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Practicing mobile first development and focusing on low css specificity for a good readability and maintainability.

**mix-blend-mode technique 👍😎**  
The image color is controled with the picture element and the css rule `mix-blend-mode`. I set a background color on the picture element and the `mix-blend-mode:multiply` on the `<img>` element. This is a very interesting and simple way to handle this type of component instead of adding an absolute positioned overlay.

**word highlight in the title 💡**  
I had a concern about the highlighted word in the title regarding accessibility as it ads verbosity when testing with voice over. The title is split in 3 parts : [1. before the highlighted word] [2. the highlighted word] [3. after the highlighted word].  
I learned that it's not an important accessible issue as it's related to the screen reader verbosity settings.

## Author

- Website - [Gwenaël Magnenat](https://www.gmagnenat.com)
- Frontend Mentor - [@gmagnenat](https://www.frontendmentor.io/profile/gmagnenat)
- LinkedIn - [@gmagnenat](https://www.linkedin.com/in/gmagnenat)

## Acknowledgments

[Grace Snow](https://www.frontendmentor.io/profile/grace-snow) for the tips about `mix-blend-mode` and the explaination about screen readers verbosity settings.
