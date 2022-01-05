# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](/images/Screenshot_2022-01-02_08-59-30.png)



### Links

- Live Site URL: [Github Page: NFT Preview Card Component](https://cybr-coder.github.io/NFT-Preview-Card-Component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Desktop-first workflow


### What I learned
From this Project, I learnt how to display an overlayed background when hovered over the main image. I listed resources later in this document...See the code below

```css
.overlay {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    height: 100%;
    width: 100%;
    opacity: 0;
    transition: 0.5s ease;
    background-color: hsl(178, 100%, 50%);
    display: flex;
    justify-content: center;
    align-items: center;
}
.container:hover .overlay{
    opacity: 1;
    cursor: pointer;
}
```

### Continued development
I am still researching to make this project responsive. I am still fairly a beginner and learning a lot now..Hope to deploy the full feature soon.

### Useful resources

- [resource 1](https://www.w3schools.com) - This helped learn how to do the image hover overlay. I really liked this pattern and will use it going forward.
- [ resource 2](https://www.developer.mozilla.org) - This is an amazing website which helped me finally understand most of the syntax I didn't know in CSS. I'd recommend it to anyone still learning this Front End Development.


## Author

- Github - [Cybr-Coder](https://github.com/cybr-coder)
- Frontend Mentor - [@cybr-coder](https://www.frontendmentor.io/profile/cybr-coder)
- Twitter - [@cybr_coder](https://twitter.com/cybr_coder)



