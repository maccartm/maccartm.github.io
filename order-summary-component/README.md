# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Order summary card solution](#frontend-mentor---order-summary-card-solution)
  - [Table of contents](#table-of-contents)
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

- See hover states for interactive elements

### Screenshot

![Solution Preview for the NFT preview card component coding challenge](https://github.com/maccartm/maccartm.github.io/blob/main/order-summary-component/order-summary-thumbnail.png)

### Links

- [Solution URL](https://github.com/maccartm/maccartm.github.io/tree/main/order-summary-component)
- [Live Site URL](https://maccartm.github.io/order-summary-component/summary.html)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

I followed the recommended design approach for this project (make sure you structure your HTML correctly in advance based on what you will need, do one CSS "section" at a time). This made things go much smoother.

Flexbox flexbox flexbox. Even after learning how useful they were in the first project that I attempted, I still tried positioning containers without `display: flex;` at first - it only led to troubles.

I made use of `position` (absolute vs. relative) and some y-shifting to have a nicer background pattern.

I tried to make use of real semantic HTML5 this time rather than just using `div` for everything. For the most part this was effective. Many of the new elements function well as containers. In some cases, though, I had to resort back to div to position elements correctly. This also helped to structure the code better - `sections`, `headers`, `footers`, etc.

### Continued development

I still have to work on margins, and not hard-coding margins all over the place (better use of viewport, % values, etc.) I feel like I define too many margins for each element inside of containers, plus the containers themselves. 

I also need to clean up my CSS code a bit - I'm sure I use many bad practices and leave redundant properties everywhere. 

I'm not sure if the way I did my `submit-button` is correct. I initially tried with a `button` element, but couldn't seem to have it grow to fit the container correctly - the `div` filled it perfectly with little effort.

### Useful resources

* [Google style guide](https://google.github.io/styleguide/htmlcssguide.html)
* [W3 CSS guide](https://www.w3schools.com/css/default.asp)
* [CSS Cheat Sheet](https://htmlcheatsheet.com/css/)
  
## Author

- Website - [Michael](https://www.your-site.com)\
