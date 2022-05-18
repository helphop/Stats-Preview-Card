# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
This was an experiment to tie together several technologies and methodologies.
### The challenge
Could I apply CUBE CSS, Every Layout, Utopia and CodyHouse to make web development easier and more organized.

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [https://github.com/helphop/Stats-Preview-Carde](https://github.com/helphop/Stats-Preview-Card)
- Live Site URL: [https://helphop.github.io/Stats-Preview-Card/main/index.html](https://helphop.github.io/Stats-Preview-Card/main/index.html)

## My process
I created scss files for layouts from Every Layout. I put these in a directory I called compositions under the css directory.

I downloaded the utilities from CodyHouse. Then I created a utils folder in my project  under the css directory. I extracted the code into files for each type of utility i.e. _typography.scss for any utilities that dealt with typography.

CodyHouse also provides a gulp.js file so I can compile my scss files. What's also nice is this gulp file uses PurgeCss so I can reduce the size of my final style.css.

I created a directory called 'blocks' under the css directory.

Finally I created a global-styles directory. I set the styles that the entire site will use and organized it into specific files, i.e. _breakpoints.scss, _reset.scss, _spacing.scss etc.

I went to

- [https://utopia.fyi/] (https://utopia.fyi/)

and used their site to create the typography scales and spacing sizes. I copied the code into css/global-styles/_typography.scss and css/global-styles/_spacing.scss.

I used

- [https://google-webfonts-helper.herokuapp.com/fonts] (https://google-webfonts-helper.herokuapp.com/fonts)

to download the Inter web font so I could self host the font.


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- CUBE CSS Methodology
- Mobile-first workflow
- Gulp
- PurgeCss
- [Every Layout](https://every-layout.dev/layouts/) - Layout Primitives - C in CUBE CSS
- [CodyHouse Utilities](https://codyhouse.co/ds/docs/framework/utilities) - CSS Framework - U in CUBE CSS
- [Utopia](https://utopia.fyi/) - For fluid typography and spacing

### What I learned
CUBE CSS methodology is easy to implement and is very helpful in organizing my code.
One of more challenging aspects of programming is naming things. CUBE CSS helps by reducing
the number of classes I need to use to create my layouts.

I learned how to apply a good balance of utility classes without cluttering up the HTML.

I also found that using the primitive layout structures from Every Layout simplified the process of going from design to development. I find I am less overwhelmed with 'how am I going to do this' and more like 'oh that's a stack, and that's a switcher'.

Finally as per the wisdom of Andy Bell and Heydon Pickering, coding a site from a design is NOT about pixel perfect results. We have no control over the devise the user will be viewing the website on.  Better to give the browser suggestions as to how to layout the site so that every user has a great experience.  This greatly reduces the amount and complexity of code while keeping the ability to be adaptable.
### Continued development

I need more practice in using this combination of technologies, especially with more challenging designs.
### Useful resources
- [Every Layout](https://every-layout.dev/layouts/) - Layout Primitives - C in CUBE CSS
- [CodyHouse Utilities](https://codyhouse.co/ds/docs/framework/utilities) - CSS Framework - U in CUBE CSS
- [Utopia](https://utopia.fyi/) - For fluid typography and spacing
- [CUBE CSS](https://cube.fyi/) - CUBE CSS methodology explained
## Author
- Frontend Mentor - [@helphop](https://www.frontendmentor.io/profile/helphop)