# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- See hover states for interactive elements

### Links

- Solution URL: (https://github.com/MohannadSambo/3-column-preview-card-component-main)
- Live Site URL: (https://mohannadsambo.github.io/3-column-preview-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- SASS
- Flexbox
- CSS Grid

### What I learned

This is the first project that I built it using HTML5 and SASS which was very intersting and fun.

Things I learned and applied in this project:

- How to use variables.
Here a code snippet of how stored the background colors in variables to reuse it.

'''scss
$sedans-background: hsl(31, 77%, 52%);
$suv-background: hsl(184, 100%, 22%);
$luxury-background: hsl(179, 100%, 13%);
'''

- How to use nesting, which you can see how in style.scss.

'''
.container {
  background-color: white;

  .sedan {

  }

  .suvs {

  }

  .luxury {

  }
}
'''

- How to extend a piece of code into another code to avoid repetion, which was a very helpful feature in SASS.

'''
.container {
  background-color: white;

  .sedan {
    font-size: 15px;
  }

  .suvs {
    @extend .sedan
  }

  .luxury {
    @extend .sedan
  }
}
'''

- How to import .scss file into another .scss file.
- How to use Grid Layout


### Continued development

- Areas I want to focus and improve my skills at future projects:

1- Grid Layout.
2- Flexbox Layout.
3- SASS Pre-processor.

### Useful resources

- [Codecademy](https://www.codecademy.com) - This helped me for leraning all HTML and CSS. I really liked this website and will use it going forward.

## Author

- Website - [Mohannad Sambo](https://mohannadsambo.github.io/3-column-preview-card-component-main/)
- Frontend Mentor - [@MohannadSambo](https://www.frontendmentor.io/profile/MohannadSambo)

