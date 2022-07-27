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
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot.png)

### Links

- Live Site URL: [https://flourishing-creponne-073eb3.netlify.app/](https://flourishing-creponne-073eb3.netlify.app/)
- Solution URL: [https://www.frontendmentor.io/solutions/stats-preview-card-scss-mobile-first-hDGRJ0ihDj](https://www.frontendmentor.io/solutions/stats-preview-card-scss-mobile-first-hDGRJ0ihDj)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid
- Mobile-first workflow
- SCSS

### What I learned

I learned how to simply switch images between mobile and desktop with the picture tag and srcset.

The default image loaded will be the one for mobile unless the viewport width has a minimal value of 53em (same as my breakpoint).

```html
<picture>
	<source srcset="images/image-header-desktop.jpg" media="(min-width: 53em)" />
	<img src="images/image-header-mobile.jpg" alt="people brainstorming" />
</picture>
```

I learned to use scss rgb function to generate color with opacity.
It outputs a rgba value in the compiled css.

```scss
$color-neutral: hsl(0, 0%, 100%); // white

.stat-label {
	color: rgb($color-neutral, 0.6); // white with a 60% opacity
}
```

I keep learning on how to structure my scss variables and build a naming convention before heading to the code.

### Continued development

I have to learn more about extend placeholders and mixins to better optimize my scss file and avoid repeating parts of the code.

## Author

- Website - [Gwenaël Magnenat](https://www.linkedin.com/in/gmagnenat/)
- Frontend Mentor - [@gmagnenat](https://www.frontendmentor.io/profile/gmagnenat)
- Twitter - [@magnenatg](https://www.twitter.com/magnenatg)
