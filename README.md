# Frontend Mentor - Equalizer landing page solution

This is a solution to the [Equalizer landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/equalizer-landing-page-7VJ4gp3DE). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Equalizer landing page solution](#frontend-mentor---equalizer-landing-page-solution)
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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![Mobile View](./screenshots/mobile-phone-ss.png)
![Tablet View](./screenshots/tablet-ss.png)
![Desktop View](./screenshots/desktop-ss.png)

### Links

- Solution URL: [GitHub Repo](https://github.com/varonalearns/Equalizer-landing-page)
- Live Site URL: [Live Site](https://equalizer-landing-page-pi.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

With this project, I learned more about how background-image works. I spent a lot of time trying to figure out how to position a background-image and came up with the code below to position bg-main-mobile.png properly:

```css
.bg-main-image {
    background-image: url("assets/bg-main-mobile.png");
    background-repeat: no-repeat;
    background-position: 0rem -14rem;
}
```

I also learned how to change the color of an svg icon on hover. That one was difficult to understand but I got something like this:

```css
svg:hover path {
  fill: var(--clr-prim-orange);
}
```

The trick was understanding that I had to include the path tag after svg:hover.

### Continued development
This project, in particular, taught me that I need to think more thoroughly when it comes to establishing responsive elements. For instance, the use of the CSS grid would have worked much better to make the project even more responsive. It is something that I will like to come back to once I have more time to do so. Right now, this project really burnt me out -- but I leared a lot and now I know where my strengths and weaknesses lie. 

### Useful resources

- [MDN Web Docs](https://developer.mozilla.org/en-US/) - This helped me with understanding how background images work and how to implement them via CSS code.
- [Team Treehouse](https://teamtreehouse.com/community/how-do-i-make-an-svg-image-change-color-when-hovering-over-the-object-tag) - This article via Team Treehous helped me with understanding how to change the color of an svg icon on hover.

## Author

- Website - [Evalia Varona](https://www.evaliavarona.com)
- Frontend Mentor - [@varonalearns](https://www.frontendmentor.io/profile/varonalearns)

