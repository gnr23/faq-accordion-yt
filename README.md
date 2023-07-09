# Frontend Mentor - 6- FAQ accordion card

This is a solution to the [FAQ accordion card](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [What I learned](#what-i-learned)

## Overview

### The challeng e

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See hover states for all interactive elements on the page
- Hide/Show the answer to a question when the question is clicked

### Screenshot

![](./src/images/tablet.png)
![](./src/images/mobile.png)
![](./src/images/bigger%20scrn.png)
![](./src/images/functionality.png)



### Links

- Solution URL: [NETLIFY URL](https://faq-accordion-card-gnr23.netlify.app)
- Live Site URL: [GITHUB URL](https://github.com/gnr23/frontend-exercise-06-faq-accordion-card)


### Built with

HTML, CSS, JS, React
VS code


### What I learned

-created a single question module

-scaling for bigger screens with media queries for menus

e.g.

@media(min-width: 992px) {
    .container {
        display: flex;  
        align-items: center;
        justify-content: center;
        min-height: 100vh;
max-width: 900px;
margin:auto;
    }

/*Also i learned this way of adding abit of responsiveness instead of togglin the images in css you can just do it in html like that8/

    function App() {
  return (
    <div className="container">
<article>
<picture>
<source media="(min-width:768px)" srcSet={desktop} /> 
<img src={mobile} alt=""/>
</picture>

"when you map over an array you create a list and every list needs to have a key"       

<SingleQuestion key={quest.id}/>

OR {quests.map((quest, index) => (
      <SingleQuestion key={index}/> 

it is preferred to use index when you know that the data is not gonna change
