# Frontend Mentor - Social proof section solution

This is a solution to the [Social proof section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-proof-section-6e0qTv_bA). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the section depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: (https://www.frontendmentor.io/solutions/understanding-css-grid-layout-FNNDpcMXj6)
- Live Site URL: (https://social-proof-section-master-nine-iota.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

For this challenge i learn that i can't solve everything whit flexbox, at first use css grid 
was very complicated and intimidating bot after a few attemps and errors i manage understand the logic
behind this

```css
.proud-of-this-css {
  .starsSection{
        color: hsl(300, 43%, 22%);
        display: grid;
        grid-template-columns: 2rem 2rem 400px 2rem 2rem;
        gap: 1rem 0;
        grid-column: 2/-1;
        grid-template-rows: repeat(3, 50px);
        font-family: 'League Spartan', sans-serif;
        font-size: 30px;
        font-weight: bold;
        padding: 20px 32px;
        justify-self: center;
        align-self: end;
    }
}
```

If you want more help with writing markdown, we'd recommend checking out (https://css-tricks.com/snippets/css/complete-guide-grid/) to learn more.

### Continued development

refine my understanding and implementation of css grid and polish my practice on html tags

### Useful resources

https://www.youtube.com/playlist?list=PLvq-jIkSeTUY628cyd9LVbXSXi2xG9mUl
https://www.youtube.com/watch?v=Fj6BGtNvXIc&t=1500s&ab_channel=VidaMRR-Programacionweb

## Author

- Website - [Julieta Galatea Calderon](https://github.com/JulietaGalatea)
- Frontend Mentor - [@JulietaGalatea](https://www.frontendmentor.io/profile/JulietaGalatea)
- Twitter - [@JulietaGCalder1](https://twitter.com/JulietaGCalder1)

## Acknowledgments

To be honest, I don't know if I can give advice on this, but I can say that if someone with limited resources and without university studies could do this, of course, you can too.

