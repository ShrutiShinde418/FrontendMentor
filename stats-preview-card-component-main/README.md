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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![stats-preview-card-component-main/Screenshot.PNG](./screenshot.jpg)


### Links

- Solution URL: https://github.com/ShrutiShinde418/FrontendMentor/tree/main/stats-preview-card-component-main
- Live Site URL: https://stats-preview-card-component-main-ruddy.vercel.app/
## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Bootstrap 4.5


### What I learned

- Using the picture tag to display content according to screen sizes.
- Responsive Web Development
- Bootstrap 4.5
- @font-face
- filter property of CSS3

```html
<picture>
                <source
                  media="(max-width:1199px)"
                  srcset="images/image-header-mobile.jpg"
                />
                <source srcset="images/image-header-desktop.jpg" />
                <img
                  src="./images/image-header-desktop.jpg"
                  class="card-img-top d-block"
                  alt="work image"
                />
              </picture>
```
```css
div img {
  border-radius: 0 10px 10px 0 !important;
  background-color: hsl(277, 64%, 61%);
  -webkit-filter: sepia(1) hue-rotate(239deg) saturate(121.7%) brightness(60%);
  filter: sepia(1) hue-rotate(239deg) saturate(121.7%) brightness(60%);
}
```



If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.


### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

- Want to work on acquiring more CSS skills
- More Responsive Web development practice


### Useful resources

- https://freecodecamp.com - This help in learning flexbox and semantic HTML.
- Coursera (Introduction to CSS by the University of Michigan) - Helped in upgrading my CSS skills
- Stack Overflow


## Author

- Frontend Mentor - [@ShrutiShinde418](https://www.frontendmentor.io/profile/ShrutiShinde418)


