# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)




## Overview

### Screenshot

![](./screenshot.jpg)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

A major learning for me on this challenge, was the idea of aligning something that in the html is at the bottom, to the top of the page.
A few simple approaches I first tried, didn't work and I considered using a flexbox but it didn't make sense. In the end I had to define the "width" and how wide it is, then the text-align attribute/method would work as intended.

Here's the code in question


```css
 .attribution{
    position: absolute;
    top:0;
    width: 100%;
    text-align: center;
    margin-top: 2px;
    font-weight: 400;
    font-family:"Outfit";
    font-size: 11px;
  }
```


### Continued development

This challenge helped me take a step back and change my approach on what to tackle first and how to set things up in html before moving onto css. It also allowed me to plan and make considerations on how things relate to one another. 

Getting the text aligned at top and center of the page gave me more trouble than I'd like to admit, and the solution was minor but I plan to carry on building my knowledge on things such as block and inline elements.


### Useful resources

- (https://www.freecodecamp.org/learn/2022/responsive-web-design/learn-css-flexbox-by-building-a-photo-gallery/step-1) - I was learning concepts within css and luckily things lined up, as this chapter was useful for how I tackled containing and grouping elements.


## Author

- Website - https://www.boyc3e.com
- Frontend Mentor - https://www.frontendmentor.io/profile/GrowingHermit44
- Twitter - https://www.twitter.com/boyc3e


