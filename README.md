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

### Screenshot
![Alt text](Screenshot%202023-03-03%20at%2020-30-54%203-%20Column%20Preview%20card%20Component%20Frontend%20Mentor.png)

### Links

- Solution URL: https://github.com/bella019/three-column-preview-card
- Live Site URL: https://bella019.github.io/three-column-preview-card/

## My process

### Built with
-Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned
Using Css Flexbox

.flex-container{
    display: flex;
    margin-top: 5rem;
    justify-content: center;
    flex-direction: row;
}
.flex-container>div{
    width: 20rem;
    height: 30rem;
    /* text-align: center; */
}
.flex-container>div:nth-child(1){
    background-color: hsl(31, 77%, 52%);
    border-radius: 1rem 0 0 1rem;
}
.flex-container>div:nth-child(2){
    background-color: hsl(184, 100%, 22%);
}
.flex-container>div:nth-child(3){
background-color:  hsl(179, 100%, 13%);
border-radius: 0 1rem 1rem 0;
}

### Continued development
Using Css flexbox

## Author
- Frontend Mentor - [@bella019](https://www.frontendmentor.io/profile/bella019)
