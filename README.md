# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![My screenshot](https://prnt.sc/9Cnj6iBNGrtd)

### Links

- Solution URL: [GitHub](https://github.com/BryanCarlos/results-summary-frontend-mentor)
- Live Site URL: [Netfily](https://beautiful-kleicha-eda01b.netlify.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

For this project, I was trying to find something that I can use more than once and I can repeat it. So I found the variables for CSS, and I use it for colors.
Thats an example I used, see below:

```css
:root {
/* Colors variables */

/* Primary */

--lightRed: hsl(0, 100%, 67%);
}

/* Here I use the variable above */
.reaction {
  color: var(--lightRed);
}
```

### Continued development

For this site, I did the responsive part when it reach 470px, for my next project I'll do the mobile first to adjust for bigger desktop monitor.


## Author

- GitHub - [BryanCarlos](https://github.com/BryanCarlos)
- Frontend Mentor - [@BryanCarlos](https://www.frontendmentor.io/profile/BryanCarlos)
- LinkedIn - [@bryan-carlos-silva](https://www.linkedin.com/in/bryan-carlos-silva//)