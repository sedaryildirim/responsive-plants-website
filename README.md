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

Code-along Challenge with Bedimcode for a Halloween website

- Responsive Plants Website Using HTML, CSS and JavaScript.
- Contains animations when scrolling.
- Includes a dark and light mode.
- Developed first with the Mobile First methodology, then for desktop.
- Compatible with all mobile devices and with a beautiful and pleasant user interface.

### Screenshot

![plants website](/preview.png)

### Links

- Solution URL: [Github Repo](https://github.com/sedaryildirim/responsive-plants-website)
- Live Site URL: [Github Pages](https://sedaryildirim.github.io/responsive-plants-website/)

## My process

### Built with

- Semantic HTML5 markup
- Mobile-first workflow
- CSS custom properties
- Grid
- Flexbox
- JS

### What I learned

- learned how to use emmet correctly with class chaining
- fixed several errors with troubleshooting for display issues
- better understanding of developer tools whilst searching for bugs
- learned more css shorthand
- better understanding of bem naming structure
- **realized how the below works**

*when .steps__card:hover is in effect, it transforms .steps__card-number by translateY(-.25rem);*

```css
.steps__card:hover .steps__card-number {
  transform: translateY(-.25rem);
}
```

- **Scroll Reveal**

*const sr identifier sets base states for SR*
*sr.reveal is called at the bottom and base stats can be changed if needed via further inline variables* 

```java
const sr = ScrollReveal({
    origin: 'top',
    distance: '60px',
    duration: 2500,
    delay: 400,
    // reset: true
})

sr.reveal('.home__data')
sr.reveal('.home__img', {delay: 500})
sr.reveal('.home__social', {delay: 600})
sr.reveal('.about__img, .contact__box', {origin: 'left'})
sr.reveal('.about__data, .contact__form', {origin: 'right'})
sr.reveal('.steps__card, .product__card, .questions__group, .footer', {interval: 100})
```

### Continued development

- research how position: relative works more in depth
- does position absolute work in the current div
- how do ::after and ::before work
- research :not

- how does overflow:hidden work
*above works by hiding items out of a set width/height of a parent container*
**questions content has a paragraph in it, its height was set to 0, then the overflow (which was the paragraph) is now hidden**

```css
.questions__content {
  overflow: hidden;
  height: 0;
}
```

### Useful resources

- [Bedimcode](https://www.youtube.com/c/Bedimcode)
- [Swiper](https://swiperjs.com/)

## Author

- Website - [Sedar Yildirim](https://github.com/sedaryildirim)
- Frontend Mentor - [@sedaryildirim](https://www.frontendmentor.io/profile/sedaryildirim)
- Twitter - [@Sdry85](https://www.twitter.com/sdry85)

## Acknowledgments

- [Bedimcode](https://www.youtube.com/c/Bedimcode)