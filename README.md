# Frontend Mentor - Meet landing page solution

This is a solution to the [Meet landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/meet-landing-page-rbTDS6OUR). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [https://github.com/norman02/meet-landing-page.git](https://github.com/norman02/meet-landing-page.git)
- Live Site URL: [https://meet-landing-page-nine.vercel.app/](https://meet-landing-page-nine.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS Grid
- Mobile-first workflow
- [Sass] (https://sass-lang.com/)

### What I learned

I leanred to use psuedo elements to create filters for background images.



```css
&::after {
        content: "";
        background-image: url('../assets/mobile/image-footer.jpg');
        background-size: cover;
        background-repeat: no-repeat;
        height: 100%;
        left: 0;
        opacity: 0.1;
        position: absolute;
        top: 0;
        width: 100%;
        z-index: -1;
    }

    &::before {
        content: "";
        background-color: $footer-bg-color;
        background-size: cover;
        background-repeat: no-repeat;
        height: 100%;
        left: 0;
        position: absolute;
        top: 0;
        width: 100%;
        z-index: -2;
    }
}
```


### Useful resources

- [CSS Tricks](https://css-tricks.com/) - This helped me learn how to use pseudo elements to create mixed background images.


## Author

- Frontend Mentor - [@norman02](https://www.frontendmentor.io/profile/norman02)
- Twitter - [@JohnIsNorman](https://www.twitter.com/JohnIsNorman)
