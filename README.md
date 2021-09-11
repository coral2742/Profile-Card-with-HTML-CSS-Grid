# Frontend Mentor - Stats preview card component solution

This is a solution to the [Profile Card Component](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### Screenshot

![](./images/Screenshot-11-09-2021.png)

![](./images/ScreenshotMobile-11-09-2021.png)


### Links

- My Solution URL: [https://www.frontendmentor.io/solutions/responsive-layout-using-html-and-css-5lZGRZ13U](https://www.frontendmentor.io/solutions/responsive-layout-using-html-and-css-5lZGRZ13U)
- Live Site URL: [https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62)

## My process

### Built with

- Semantic HTML5 markup
- Google Fonts
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

I learned to...

· Define colors as variables:

```css
:root{
    --VeryDarkBlue: hsl(233, 47%, 7%);
    --DarkDesaturatedBlue: hsl(244, 38%, 16%);
    --SoftViolet: hsl(277, 64%, 61%);
    --White: hsl(0, 0%, 100%);
    --SlightlyTransparentWhite: hsla(0, 0%, 100%, 0.75);
    --SlightlyTransparentWhite: hsla(0, 0%, 100%, 0.6);
}
```

· Highlight a word into a text changing the word's color and using "span":
  
  ```html
  <h1>Get <span>insights</span> that help your business grow.</h1>
  ```
  
  ```css
  .textos span{
    color: var(--SoftViolet);
}
  ```

· Colorize an image with a solid color:

```css
.imagen{
    position: relative;
}

.imagen::after{
    position: absolute;
    content: '';
    height: 100%;
    width: 100%;
    left: 0;
    right: 0;
    background-color: var(--SoftViolet);
    opacity: .5;
}
```



### Continued development

This was the first challenge I focused using HTML and CSS from the platform [Frontend Mentor](https://www.frontendmentor.io/challenges).



### Useful resources

- [Página web de Manz.dev](https://manz.dev/) - This helped me finding information about HTML and CSS with the cheatsheet posted. Thanks @ManzDev



## Author

- Github - [Coral2742](https://github.com/coral2742)
- Frontend Mentor - [@coral2742](https://www.frontendmentor.io/profile/coral2742)
- Instagram - [@coral2742](https://www.instagram.com/coral2742)
- Twitter - [@coral2742](https://twitter.com/coral2742)
