# Frontend Mentor - Tech book club landing page solution

This is a solution to the [Tech book club landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/tech-book-club-landing-page-fZQidjHU73). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Tech book club landing page solution](#frontend-mentor---tech-book-club-landing-page-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./assets/images/solution-screenshot.png)

### Links

- Live Site URL: https://roaring-starship-5c5c37.netlify.app/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Popover API & Anchor Positioning
- Container Queries

### What I learned

1. I used a more advanced content grid layout that accomodates for a narrow colum (Membeship Options and Quote section). Setting up the grid is still abit difficult but the end result is very worth it, will need some more practice to get used to it
2. For the tech logos in the third section i used anchort positioning that also has a fallback option when the layout changes. One caveat is that the tech logos stay in the fallback position when resizing to bigger screens... it only recalculates after a refresh
3. For the glow: i used a gradient background instead, since positioning the glow globally turned out to be difficult. Sometimes you gotta think out of the box!
