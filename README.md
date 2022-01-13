# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

## My process

### Built with

- Semantic HTML markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

```html
Some HTML code I'm proud of
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NFT Preview Card</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" href="favicon-32x32.png">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Outfit&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@100;400;500&display=swap" rel="stylesheet">
</head>

<body>
    <div class="division">
        <img class="image" src="image-equilibrium.jpg" alt="equilibrium-image">
        <h1 class="para1">Equilibrium #3429</h1>
        <p class="para2">Our Equilibrium collection promotes balance and calm.</p>
        <svg width="11" height="18" xmlns="http://www.w3.org/2000/svg">
            <path d="M11 10.216 5.5 18 0 10.216l5.5 3.263 5.5-3.262ZM5.5 0l5.496 9.169L5.5 12.43 0 9.17 5.5 0Z"
                fill="#00FFF8" /></svg>
        <p class="para3">0.041 ETH</p>
        <svg class="clock" width="17" height="17" xmlns="http://www.w3.org/2000/svg">
            <path
                d="M8.305 2.007a6.667 6.667 0 1 0 0 13.334 6.667 6.667 0 0 0 0-13.334Zm2.667 7.334H8.305a.667.667 0 0 1-.667-.667V6.007a.667.667 0 0 1 1.334 0v2h2a.667.667 0 0 1 0 1.334Z"
                fill="#8BACD9" /></svg>
        <p class="para4">3 days left</p>
        <hr class="hr">
        <img class="avatar" src="image-avatar.png" alt="avatar-image">
        <p class="para5"> <span class="span">Creation of</span> Jules Wyvern</p>

    </div>


</body>
</html>
  
```

```css
.proud-of-this-css body {
body {
    background-color: hsl(217, 54%, 11%);
}

.division {
    background-color: hsl(216, 50%, 16%);
    height: 535px;
    width: 310px;
    padding: 20px;
    margin-left: 510px;
    margin-top: 30px;
    border-radius: 25px;

}

.image {
    width: 290px;
    height: 270px;
    margin: 10px 0px 10px 10px;
    border-radius: 15px;

}

.para1 {
    color: hsl(0, 0%, 100%);
    font-size: 18px;
    font-family: 'Outfit', sans-serif;
    font-weight: 580;
}

.para1:hover {
    color: hsl(178, 100%, 50%);
}

.para2 {
    color: hsl(215, 51%, 70%);
    font-family: 'Outfit', sans-serif;
    font-size: 18px;
    font-weight: 300;
    clear: left;
}

.para3 {
    display: inline-block;
    color: hsl(178, 100%, 50%);
    font-size: 18px;
    font-family: 'Outfit', sans-serif;
    font-weight: 550;
}

.para3:hover {
    color: azure;
}

.clock {
    margin-left: 90px;
}

.para4 {
    display: inline-block;
    color: hsl(215, 51%, 70%);
    font-size: 18px;
    font-family: 'Outfit', sans-serif;
    font-weight: 350;
}

.para5 {
    font-size: 18px;
    color: hsl(0, 0%, 100%);
    font-weight: 350;
    font-family: 'Outfit', sans-serif;
}

.para5:hover {
    color: hsl(178, 100%, 50%);
}

.hr {
    width: 95%;
    background-color: hsl(215, 32%, 27%);
    border-style: none;
    height: 1px;

}

.span {
    color: hsl(215, 51%, 70%);
    font-size: 18px;
    font-family: 'Outfit', sans-serif;
    font-weight: 300;
}

.avatar {
    width: 50px;
    height: 50px;
    float: left;
    margin-right: 20px;
    border: 20px;
}
```

### Useful resources

-(https://www.w3schools.com/html/html_css.asp) - This helped me for styling the website. I really liked this website and will use it going forward.

- (https://developer.mozilla.org/en-US/docs/Web/HTML) - This is an amazing article which helped me finally understand HTML. I'd recommend it to anyone still learning this concept.
