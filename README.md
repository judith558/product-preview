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
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Desktop Preview](./design/desktop-preview.jpg)
![Mobile Preview](./design/mobile-design.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/yourusername/product-preview-card-component)
- Live Site URL: [Live Demo](https://yourusername.github.io/product-preview-card-component)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Responsive design with media queries

### What I learned

This project reinforced my understanding of responsive web design and CSS Flexbox. I learned how to use the `<picture>` element for responsive images and how to implement hover states effectively.

```html
<picture>
  <source media="(min-width: 768px)" srcset="./images/image-product-desktop.jpg">
  <img src="./images/image-product-mobile.jpg" alt="Gabrielle Essence Eau De Parfum">
</picture>
```

```css
.btn:hover {
  background-color: hsl(158, 42%, 18%);
}
```

### Continued development

I want to continue focusing on accessibility in future projects, ensuring all interactive elements have proper focus states and the design meets WCAG guidelines.

### Useful resources

- [Frontend Mentor](https://www.frontendmentor.io) - For providing this challenge and improving coding skills.
- [Google Fonts](https://fonts.google.com) - For the Montserrat and Fraunces fonts used in the design.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)

## Acknowledgments

Thanks to Frontend Mentor for the challenge and the community for inspiration.
