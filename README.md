# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Stats preview card component solution](#frontend-mentor---stats-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshots](#screenshots)
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

### Screenshots

![Desktop](https://i.imgur.com/LmjRhAS.png)
![Mobile](https://i.imgur.com/P30L3px.png)

### Links

- Solution URL: [Here](https://rhiino1.github.io/frontendmentor-stats-preview-card/)
- Live Site URL: [Here](https://rhiino1.github.io/frontendmentor-stats-preview-card/)

## My process

This time i just setted up the project, taking as a blueprint the last one. This was very simple but always helpful project and I set an estimated time of 5 hours. Today, my workflow this time was mobile first, never used it and i want to try it.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [SASS](https://sass-lang.com/) - CSS library

### What I learned

Mobile Workflow it's a pretty way to work, really feel it faster than the last time, when i was doing mobile and destkop at the same time. Looking the "pink" filter on the image i struggle a bit, then research and found that I can make a new background on after, so I did it and works fine:

```scss
  &::after {
    content: "";
    position: absolute;
    border-radius: rem(10) rem(10) 0 0;
    width: rem(327);
    height: rem(240);
    background: hsl(277deg 96% 43% / 40%);
      
    @include breakpoint(large) {
      border-radius: 0 rem(10) rem(10) 0;
      width: rem(540);
      height: rem(446);
    }
  }
```

The only problem was i couldn't get the exact color, I really try it with brutforce because I don't know any way to do that. so something I want to fix in future.

### Continued development

As I mentioned above, I want to research about colors and hsl, since I am a programmer I used hex color so I want to change that.

### Useful resources

- [Resource 1](https://bryanlrobinson.com/blog/how-to-css-after-elements-for-background-overlays/) - This is a tutorial to make background on after elements, this was really helpful with my image.
- [Resource 2](https://www.w3schools.com/html/html5_semantic_elements.asp) - Semantic HTML5 Markup. I tried this time too and I guess did it properly.

## Author

- Github - [Cesar SC](https://github.com/Rhiino1)
- Frontend Mentor - [@Rhiino1](https://www.frontendmentor.io/profile/Rhiino1)
- Twitter - [@Rhiino_1](https://www.twitter.com/Rhiino_1)