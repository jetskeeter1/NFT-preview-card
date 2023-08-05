# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

  This challenge is all about making the preview card component for a nft along with the hover overlay effect that shows the icon-view along with a background color of cyan and pointer.

### The challenge

- hover state that changes the image

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

  The process that I took to making this preview card is to use the flexbox that I have been using from my previous solutions to other challenges related to cards or preview cards which it gives me the exact result by using the flex, flex-wrap, and defining the width value to fit all in proportion to the image in the card itself. Everything else was relatively easy until I had to find some methods to create an overlay when hovering the image and found that hover chaining was the best method for its simple solution.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

What I learned is the difficulties of trying to get the same result as the background colors and box-shadows that I am trying to get.

I learned that I can be completely stupid sometimes when I working on how to center icon-view.svg because I did not realized that the .container-image did not get its defined width and height, which I had used translate to get the desired result, but as soon as I had noticed that I gave a value to height, I smack my face for not realizing. In the end, I used flexbox to center the element div.

I learned that I can chain the hover to another element div such as the .overlay div which gave me the hover effect.

## Useful resources

Centering element div:
- https://blog.hubspot.com/website/center-div-css
  (I found plenty of different ways to centering a div element, but decided to use tranform:translate(); to get the center div that I want.)

## Author

- Website - (https://www.your-site.com)
- Frontend Mentor - (https://www.frontendmentor.io/profile/jetskeeter1)
- Instagram - (https://www.instagram.com/jetskeeter9/?hl=en)

## Acknowledgments

N/A
