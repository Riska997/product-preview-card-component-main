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

![alt text](images/screenshot.JPG)

### Links

- Solution URL: [Github](https://github.com/Riska997/product-preview-card-component-main.git)
- Live Site URL: [Github Pages](https://riska997.github.io/product-preview-card-component-main/)
- Live Site URL: [Netlify](https://stellular-fudge-7066be.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

I learned how to effectively use CSS Grid and Flexbox for layout purposes. Additionally, I improved my understanding of responsive design principles.


```css
.main {
    display: grid;
    grid-template-columns: 1fr 1fr;
    border-radius: 20px;
    overflow: hidden;
    background-color: hsl(0, 0%, 100%);
    max-width: 1200px;
    width: 100%;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.image {
    grid-column: 1/2;
}

.image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.content {
    grid-column: 2/3;
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 40px;
}
```


### Continued development

In future projects, I aim to further enhance my knowledge of JavaScript and explore advanced CSS techniques.

### Useful resources

- [W3schools](https://www.w3schools.com/css/css_grid.asp) - This helped me for grids. 


## Author

- LinkedIn - [Prisca Mulishi](www.linkedin.com/in/prisca-mulishi-3994702a2)
- Frontend Mentor - [@Riska997](https://www.frontendmentor.io/profile/Riska997)


