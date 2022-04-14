# Huddle landing page

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Huddle landing page](#huddle-landing-page)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Useful resources](#useful-resources)
  - [Author](#author)
  - [Examples:](#examples)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](demo/huddle-landing-page.png)

### Links

- Live Site URL: [https://youthful-goldberg-0553c4.netlify.app/](https://youthful-goldberg-0553c4.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Responsive Web Design
- Flexbox
- [Figma](https://www.figma.com/) - Tool for site mockup

### What I learned

To see how you can add code snippets, see below:

Practice structuring my class names to be maintainable and avoided naming collisions.
```html
<section class="hero">
  <div class="hero-content">
    <img class="hero-image"/>
    <div class="hero-info">
      <button class="hero-button"></button>
    </div>
  </div>
</section>
```

Using CSS Variables to reduce a lot of repetitive CSS. This also allows me to be able to make minimal css edits and for my CSS tweaks to have an impact quickly.
```css
:root {
  --violet: hsl(257, 40%, 49%);
  --soft-magenta: hsl(300, 69%, 71%);
  --socials-hover: hsl(322, 100%, 66%);
  --white: hsl(0, 0%, 100%);
  --head-font: "Poppins", sans-serif;
  --head-size: 2.5rem;
  --body-font: "Open Sans", sans-serif;
  --body-size: 1.125rem;
}
```

### Useful resources

- [CSS Tricks Custom CSS Properties](https://css-tricks.com/a-complete-guide-to-custom-properties/) - Kept this guide on the side for any questions I had when working with custom CSS variables.
- [CSS Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This is another guide I always use for really any project.

## Author

- Website - [Mario Ballesteros](https://mariob.me/)
- Frontend Mentor - [@ohmymario](https://www.frontendmentor.io/profile/ohmymario)
<!-- - Twitter - [@yourusername](https://www.twitter.com/yourusername) -->

## Examples:
Take a look at these couple examples that I have in my own portfolio:

**weatherman:** https://github.com/ohmymario/weatherman

**Coffee Roasters:** https://github.com/ohmymario/coffee-roasters

**qr-code:** https://github.com/ohmymario/qr-code