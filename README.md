# Frontend Mentor - Skilled e-learning landing page solution 
![Static Badge](https://img.shields.io/badge/Challenge-Front_End-blue)

This is a solution to the [Skilled e-learning landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/skilled-elearning-landing-page-S1ObDrZ8q). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
    - [Desktop Layout](#desktop-layout)
    - [Tablet Layout](#tablet-layout)
    - [Mobile Layout](#mobile-layout)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [To-Do](#to-do)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot
- #### Desktop Layout
<img src="./img/Desktop-Layout.png" alt="Desktop Layout" style="display: block; margin: 0 auto; height:400px;">

- #### Tablet Layout

<img src="./img/Tablet-Layout.png" alt="Tablet Layout" style="display: block; margin: 0 auto; height:400px;">


- #### Mobile Layout
<img src="./img/Mobile-Layout.png" alt="Mobile Layout" style="display: block; margin: 0 auto; height:800px;">


### Links

- Website URL: [To Implement](#to-do)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow
- [Sass](https://sass-lang.com/) - CSS extension

### What I learned

My main focus on the project was to use a CSS extension in order to write cleaner code, as well as practice my Front-End developer skills by, giving a Figma model, create the html and css to get the desired view of the page. I used [Sass](https://sass-lang.com/) to achieve this in which I learned how to use the next funcionalities in Sass:

- Variables

```scss
// Heading
$heading-font-color: #13183f;
$heading-font-weight: weight(extra-bold);

//Body
$body-font-color: #83869A ;
```

- Mixins

```scss
@mixin tablet {
    @media only screen and (max-width: $tablet-size){
        @content;
    }
}

@mixin mobile {
    @media only screen and (max-width: $mobile-size){
        @content;
    }
}
```
- Functions
```scss
@function weight($weight-name){
    @return map-get($plus-jakarta-sans-weights , $weight-name);
}
```
- Extensions
```scss
.btn3 {
    @extend .btn2;
    background: $gradient2;
}
```

### Continued development

Throughout the challenge in order to position and align elements like the cards I used the grid and flexbox methods in CSS.

I would love to refine my use of this two concepts and get more comfortable with them in order to finish responsive websites faster, and with better quality.

I would also like to incorporate elements like animations and scroll effects to my next projects.

### Useful resources

- [CSS-Tricks Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - This helped me with the grid design, since its a cheatsheet of the basics of using grid in CSS. I really liked how well explained it is and the examples it gives.

- [CSS-Tricks Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This is another resourse from the same page, that focuses on the Flexbox system. As well as the grid one, they explained the concepts really well and the examples are easy to understand.

## Author

- Website - [Hugo S Juarez P](#to-do)
- Frontend Mentor - [@HugoSJuarez](https://www.frontendmentor.io/profile/HugoSJuarez)
- Linkedin - [Hugo Juarez](https://www.linkedin.com/in/hugo-juarez-934787269/)

## To-Do

- [x] Finish the challenge
- [ ] Make portfolio website
- [ ] Upload it to the portfolio website