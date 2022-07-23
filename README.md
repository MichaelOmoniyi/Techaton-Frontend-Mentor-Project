# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](images/Screenshot_20220723-211136.png)

### Links

- Solution URL: [Add solution URL here](https://michaelomoniyi.github.io/Techaton-Frontend-Mentor-Project/)
- Live Site URL: [Add live site URL here](https://michaelomoniyi.github.io/Techaton-Frontend-Mentor-Project/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- [Font Awesome](https://fontawesome.com/)
- [Google Fonts](https://googlefontd.com/)


### What I learned



```html
  <link rel="preconnect" href="https://fonts.googleapis.com">
   <i id="facebook" class="fa-brands fa-facebook-f"></i>
```
```css
  :root {
  --Violet: hsl(257, 40%, 49%);
  --softMagenta: hsl(300, 69%, 71%)
}
.icon i:hover{
  background-color: var(--softMagenta);
  border-color: var(--softMagenta);
}
@media only screen and (max-width: 375px;){
  .container{
    flex-direction: column;
    height: auto;
  }
  .image{
    width: 100%;
  }
  .main{
    background-image: url('/images/bg-mobile.svg');
    background-size: cover;
    background-repeat: none;
    background-color: var(--Violet);
    width: 100%;
  }
}    
```


### Continued development
I would love to master the use of vh, media queries, display and the <i> tag.


### Useful resources

- [Example resource 1](https://www.w3schools.com) - This helped me regarding creating border for the social media icons.


## Author

- Website - [Michael Omoniyi](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@Omons_Mikel](https://mobile.twitter.com/Omons_Mikel)


## Acknowledgments
Ace Adonis - Mentor at Techaton
Hillary - Fellow member at techaton
