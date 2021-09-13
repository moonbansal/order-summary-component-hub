# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](order-summary-component-hub/image.png)

### Links

- Solution URL: (https://github.com/moonbansal/order-summary-component-hub)
- Live Site URL: (https://order-summary-component-hub.vercel.app)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Bootsrap

### What I learned

```html


<div class="row" id="plan">
            <div class="col-sm" id="img">
              <img src="images/icon-music.svg" />
            </div>
            <div class="col-sm" id="text">
              Annual Plan
              <span id="rate">$59.99/year</span>
            </div>
            <div class="col-sm" id="link">
              <a href="#">Change</a>
            </div>
          </div>


```


```css


@media (min-width: 375px) and (max-width: 670px) {
  #main {
    background-size: contain;
    background-color: hsl(225, 100%, 94%);
    display: flex;
    justify-content: center;
    align-items: center;
    height: 600px;
  }
  #card-container {
    width: 360px;
    height: 570px;
  }
  #plan {
    width: 270px;
    font-size: x-small;
  }
}


```


### Continued development

- Flexbox 
- Bootstrap 
- Media queries 


## Author

- Website - Moon Bansal 
- Frontend Mentor - [@moonbansal](https://www.frontendmentor.io/profile/moonbansal)
