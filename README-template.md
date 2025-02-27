# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge) 
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

- See hover and focus states for all interactive elements on the page


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- HTML5
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

What I learned from this project is the intricacies of styling with CSS. Purely styling a website
with CSS and not relying on pre-built, pre-stylized elements was a rewarding challenge.

Also, how I tackled the dropshadow behind the card was funny after all was done. I lined up
the dropshadow with the blogCardContainer because I couldn't figure out how to dropshadow just the card.
If I implemented the dropshadow inside blogCardContainer, all elements were getting dropshadowed. So this
was a creative workaround I came up with to tackle this challenge. (code below)

    .blogCardContainer {
      border: 1px solid black;
      background-color: white;
      border-radius: 16px;
      height: 550px;
      width: 400px;
      position: relative;
      z-index: 2;
    }

    .dropshadow {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      position: absolute;
      z-index: 1;
      background: black;
      border-radius: 16px;
      height: 550px;
      width: 400px;
      filter: drop-shadow(0.5rem 0.5rem);
      left: 689px;
    }

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

### Continued development

In future projects I will try to tackle understanding dropshadow more and how to separate the classes better to not have all assets become dropshadowed.
Also, I would love to continue delving into flexboxes and understanding how to use it to my advantage to manipulate elements. 

### Useful resources

- [CSS Tricks](https://css-tricks.com/how-to-stack-elements-in-css/) - This helped me get a better grasp of stacking elements in CSS. I utilized this to create the
dropshadow effect in my own peculiar way. 
- [Flexbox Froggy](https://flexboxfroggy.com/) - This is an amazing little game that helps me refresh my skills on flexboxes. I play it every so often to refresh
myself on the techniques possible with flexboxes. 


## Author

- Website - [David Popovici](https://www.your-site.com)
- Github - [davidpopo1](https://github.com/davidpopo1)
