# Frontend Mentor - Testimonials Grid Section Solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7no7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the site depending on their device's screen size.
- See hover states for all interactive elements on the page.

### Screenshot

![Design Preview](./design/desktop-preview.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/HatemRishah/Grid_Sections.git)
- Live Site URL: [Live Demo on Netlify](https://gridsyssections.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS Custom Properties
- CSS Grid (Layout Architecture)
- Flexbox (Component Alignment)
- Mobile-first workflow
- Google Fonts (Barlow Semi Condensed)

### What I learned

In this project, I focused on mastering the **CSS Grid Layout**. I learned how to create a complex 4-column layout and transform it into a single-column stack for mobile devices using Media Queries.

Key takeaway for the Grid spanning:
```css
#one {
  grid-area: 1 / 1 / 2 / 3; /* Spanning two columns for Daniel */
}