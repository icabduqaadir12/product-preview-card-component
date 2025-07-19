# Frontend Mentor - Product preview card component solution

This is my solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). It's a beginner-friendly challenge that helped me practice responsive layouts and semantic HTML structure.

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
- See hover and focus states for interactive elements

### Screenshot

![Product Preview Card Screenshot](./screenshot.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/icabduqaadir12/product-preview-card-component)
- Live Site URL: [View Live](https://icabduqaadir12.github.io/product-preview-card-component/)

## My process

### Built with

- Semantic HTML5
- SCSS (Sass)
- Flexbox
- Mobile-first workflow
- Responsive image rendering using `<picture>` element

### What I learned

- Using semantic HTML tags like `<main>`, `<section>`, and `<picture>` improves accessibility and structure.
- The `<picture>` element with `<source>` is useful for responsive image switching.
- SCSS variables make it easier to manage design tokens (e.g., colors, fonts).
- Flexbox layout adjustments via media queries enable smooth mobile-to-desktop responsiveness.

Example SCSS snippet:

```scss
$primary-color: hsl(158, 36%, 37%);

.add_to_cart {
  background-color: $primary-color;

  &:hover {
    background-color: hsl(158, 42%, 18%);
  }
}
```

### Continued development

- Improve use of BEM naming convention in SCSS for larger projects
- Explore using CSS Grid in combination with Flexbox for more complex layouts
- Focus more on accessibility best practices (semantic HTML, ARIA roles, keyboard navigation)
- Practice more on optimizing responsiveness for devices under 375px width

## Author

- Frontend Mentor - [@icabduqaadir12](https://www.frontendmentor.io/profile/icabduqaadir12)
- GitHub - [icabduqaadir12](https://github.com/icabduqaadir12)
