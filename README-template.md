# Frontend Mentor - Sunnyside agency landing page solution

This is a solution to the [Sunnyside agency landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/sunnyside-agency-landing-page-7yVs3B6ef). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Extra challenges](#extra-challenges)
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

- View the optimal layout for the site depending on their device's screen size.
- See hover states for all interactive elements on the page.

### Extra challenges

As a bonus I want to achieve the following extra challenges:

- The page must be accessible according to WCAG 2.1 standards, things like color contrast, skip links, clear element focus, keyboard navigation support and necessary aria attributes.
- I want to add minimal animations to the page, such as a toggle animation on the responsive menu and transforms on various content on the page using the IntersectionObserver.
- As a bonus challenge I want to make the navigation sticky when you scroll past the hero section
- And as another bonus challenge I want to add a revealing effect on the footer, so that it seems like it's sliding into view from behind the rest of the page

### Screenshot

<!-- ![](./public/assets/social-image-preview.png) -->

### Links

- [Solution URL]()
- [Live Site URL]()

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- WCAG 2.1 best practices
- CSS Animations
- JavaScript IntersectionObserver API
- [Astro](https://astro.build) - Astro Static Site Generator
- [Accessible Astro Starter](https://github.com/markteekman/accessible-astro-starter) - My own starter template for Astro

### What I learned

- I learned that when mapping colors in SCSS, if you use an actual color name (such as yellow instead of dark-yellow), you need to either use them as strings or map keys:

```scss
$colors: (
  primary: (
    yellow: hsl(194, 100%, 80%), // not how you do it
    "yellow": hsl(194, 100%, 80%), // should be quoted
    // ...
  ),
  neutral-clr: (
    // ...
  ),
);
```

### Continued development

- ...

### Useful resources

- [Intersection Observer API](https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API) - The MDN documentation on how to use the Intersection Observer API.
- [Intersection Observer Example](https://codepen.io/markteekman/pen/jOyXKpE) - An example I made in a CodePen of how to use the Intersection Observer.

## Author

- [Personal Website](https://www.markteekman.nl)
- [Frontend Mentor Profile](https://www.frontendmentor.io/profile/markteekman)
- [LinkedIn Page](https://nl.linkedin.com/in/markteekman)
- [GitHub Projects](https://github.com/markteekman)
- [NPM Packages](https://www.npmjs.com/~markteekman)
- [CodePen Creations](https://codepen.io/markteekman)
