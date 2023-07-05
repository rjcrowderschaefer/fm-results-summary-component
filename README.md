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
- See hover and focus states for all interactive elements on the page

### Screenshot

![Mobile view](https://i.imgur.com/muZmaBp.png)
![Desktop view](https://i.imgur.com/qzCDQoK.png)

### Links

- [GitHub Repo](https://github.com/rjcrowderschaefer/fm-results-summary-component)
- [Live Site URL](https://rjcrowderschaefer.github.io/fm-results-summary-component/)

## My process

This was my first project where I intentionally begin the development process with a mobile-first approach so that I could get used to industry standards and understand how to adjust the look & feel based on major breakpoints using media queries. I found it much simpler to start with the mobile breakpoint CSS and then add layers of CSS media queries to account for non-mobile screen sizes. For this project, I focused on two media queries: min-width 900px for desktop and min-width 450px for tablets.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Through this project I was able to successfully implement a mobile-first approach and put into practice standards that I have frequently been learning about. The design, although faily simple, required me to research and implment a few CSS declarations that I previously hadn't used very often. I also practiced DRY code, deciding when to use a single class to target multiple areas of the design as well as when to use an id or class selector.

I'm continuing to develop my understanding of the parent and child relationship with HTML elements, specifically when it comes to placement and orientation of child elements (divs, etc) within a parent container.

```html
<h1>Some code snipets that I'm proud of:</h1>
```
```css
.score-circle {
    display: inline-block;
    background-image: linear-gradient(to bottom, rgba(0,0,0,.25), rgba(0,0,0,0));
    border-radius: 50%;
    width: 35%;
    height: 38%;
    margin-top: 20px;
}
```

```css
.button:hover {
    background-image: linear-gradient(#6842ff, #3229ea);
    cursor: pointer;
}
```

### Continued development

I intentially did not leverage the JSON file and instead opted to hardcode the "Summary" section content in order to focus my practice on HTML and CSS specifically. I future projects I will look to leverage Javascript to dynamically incorporate JSON and remove the need to hardcode certain aspects of the content within the HTML file.

## Author

- LinkedIn - [RJ Crowder-Schaefer](https://www.linkedin.com/in/rjcrowderschaefer/)
- Frontend Mentor - [@rjcrowderschaefer](https://www.frontendmentor.io/profile/rjcrowderschaefer)
- GitHub - [@rjcrowderschaefer](https://github.com/rjcrowderschaefer)