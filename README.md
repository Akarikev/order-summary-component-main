# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- See hover states for interactive elements

### Screenshot

![](<./Screenshots/Screenshot%20(21).png>)
![](<./Screenshots/Screenshot (22).png>)

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/order-summary-compnent-gwfyLyceQK)
- Live Site URL: [Add live site URL here](https://ordersummaryfrontendm.netlify.app/)

## My process

First, i drew out an overview of the project, to make sure am following the html and css rules. I layered down the html components and separated all components into their respectives.
I worked on, desktop first, to be sure with the margins and paddings of respective components, also, to see active hover states for elements. The responded correctly in their active states. I added the basic CSS properties first, before ensuring to add other complex properties.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow

### What I learned

Though this was a simple challenge, i sort of find it challenging especially with the Media Queries. I learnt that, All devices follow certain rules for HTML and CSS, and that i think should be respected, if one wants to create, a very responsive project.
Also, I learnt, the use of FlexBox is quite important for responsive designs and workflow.

To see how you can add code snippets, see below:

```html
<div class="payment-plan">
  <div class="favicon">
    <img src="/order-summary-component-main//images/icon-music.svg" alt="" />
  </div>
  <div class="plan">
    <h4>Annual Plan</h4>
    <p>$59.99/year</p>
  </div>
  <div class="change-plan">
    <a href="#">Change</a>
  </div>
</div>
<div class="btns">
  <div class="proceedbtn">Proceed to Payment</div>
  <div class="cancelbtn">Cancel Order</div>
</div>
```

```css
.container {
  max-width: 1100px;
  display: flex;
  flex-direction: column;
  width: 29%;
  background-color: #fff;
  /*display: grid;
    grid-template-rows: 1fr 1fr;
    */
  border-radius: 15px;
  overflow: hidden;
  margin: 1rem;
  height: 10%;
}
```

```css
@media screen and (max-width: 728px) {
  body {
    background: url(/order-summary-component-main//images/pattern-background-mobile.svg);
    background-repeat: no-repeat;
    background-color: hsl(225, 100%, 94%);
    background-size: contain;
  }
  .container {
    width: 66%;
  }
  .main {
    font-size: 15px;
    padding: 1rem;
  }
}
```

### Continued development

I want to continue focusing on the use of css flexbox and media queries, generally, focus on responsive designs. Though this is my first, i would like to learn more from anyone out there!

### Useful resources

- [resource 1](https://www.w3schools.com) - This helped me for writing media queries. I really liked this pattern and will use it going forward. This is an amazing article which helped me finally understand flexblox and, positioning. I'd recommend it to anyone still learning this concept.

## Author

- Frontend Mentor - [@Akarikev](https://www.frontendmentor.io/profile/Akarikev)
- Twitter - [@elorm_elom](https://www.twitter.com/elorm_elom)

## Acknowledgments

Thanks to the internet, for helping, me not cry out or loose hope!
