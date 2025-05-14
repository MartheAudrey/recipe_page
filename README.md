# Frontend Mentor - Recipe page

![Design preview for the Recipe page coding challenge](./preview.jpg)

## Welcome! 👋

## Table of contents

- [Overview](#overview)
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

### Screenshot

![Recipe page screenshot](/recipe_project-screenshot.png)

### Links

- Solution URL: [Frontmentor solution](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm)
- Live Site URL: [What I did](https://martheaudrey.github.io/recipe_page/)

## My process

1. Understand the challenge
2. Build the HTML structure
3. Style everything with CSS

### Built with

- Semantic HTML5 markup
- CSS custom properties


### What I learned

1. An h1 element that is a descendant of either article, aside, nav or section element,has a font size set to a default of 1.17em by the user agent stylesheet of Chrome's webkit. I had to specify the size of the h1 element in my custom stylesheet.

    ```css
    .title-description-container h1{
    margin: 30px 0;
    font-size: clamp(1.75rem, 1.679rem + 0.36vw, 2rem);
    font-family: YoungSerif-Regular;
    }
    ```
2. How to change bullet color of unordered lists

    ```css
    .ingredients ul li::marker{
    color: var(--brown-800);
    }
    ```

3. How to set a border to the top and bottom sides

     ```css
    .instructions{
    border-style: solid none;
    border-color: var(--stone-150);
    border-width: 1px;
    padding: 22px 0;
    }
    ```

### Continued development

In next projects I would like to learn new CSS properties and concepts.

### Useful resources

- [Why h1 elements appear smaller in <section> elements](https://maryamakodu.hashnode.dev/why-h1-elements-appear-smaller-in-section-elements) - This helped me to understand why my h1 didn't display as it ought to. The topic is well explained. I recommend it.
- [Change bullet color of list](https://www.w3schools.com/HOWTO/howto_css_bullet_color.asp) - This course by W3schools helped to change the color of my list's bullets.
- [border-style](https://developer.mozilla.org/en-US/docs/Web/CSS/border-style#values) - I learnt how to use border-style property. It was a first for me.


## Author

- Frontend Mentor - [@MartheAudrey](https://www.frontendmentor.io/profile/MartheAudrey)


## Acknowledgments

I would like to thank :
- Maryama Kodu for her article
- W3schools and mdn for their online courses
