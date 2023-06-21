# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [https://github.com/Timilehin2509/results-summary-component-main](https://github.com/Timilehin2509/results-summary-component-main)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I am not sure how optimized my mobile layout will be, but my desktop layout should be alright (I was on a time-limit). I created a flexbox with dimensions relative to the viewport but elements with fixed dimensions.
The flexbox aligns the elements within its borders and has an "overflow:auto" to prevent it from affecting 
the footer. I created 2 main boxes within the flexbox, one with the basic score and the other with the individual ones; I have no Javascript knowledge so the data.json file was not used; each box and the elements within have fixed sizes, so that will definitely affect mobile viewing at this point in time.
The left box backgrounds are linear gradients created using the included color styles.
The right box link has a linear gradient as its hover state.
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### Continued development

I would like to continue working on my flexbox techniques, as well as media queries and element sizing and positioning. I have the rudiments down as of now, but I'm pretty sure I miseed a few things out that would have simplified my work (though I'm not sure what exactly.)

### Useful resources

- [Flexbox](https://www.w3schools.com/css/css3_flexbox.asp) - This helped me understand how to fit content in browser windows.

## Author

- Frontend Mentor - [@Timilehin2509](https://www.frontendmentor.io/profile/Timilehin2509)
- Github - [Oluwatimilehin Aina](https://github.com/Timilehin2509)


## Acknowledgments

I'd like to thank W3Schools for teaching me indirectly about CSS techniques.
It's not perfect, but it will only get better as I progress.

