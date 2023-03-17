# Frontend Mentor - Interactive rating component solution

This is a solution to the [Interactive rating component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/interactive-rating-component-koxpeBUmI). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Select and submit a number rating
- See the "Thank you" card state after submitting a rating

### Screenshot

![](screenshot/Screenshot (56).png)
![](screenshot/Screenshot (57).png)
![](screenshot/Screenshot (59).png)
![](screenshot/Screenshot (60).png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I was able to create a div for the rating section and then used section for the thank you section. I also made my design responsive to any gadget.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- JavaScript

### What I learned

During this project, i was able to learn how to make a responsive workflow into desktop site and mobile device. I was also able to learn how to change color when the numbers are click using JS.

```html
<h1>Some HTML code I'm proud of</h1>
```
```css
@media(max-width:500px){
    h2 {
        font-size: 30px;
    }

    body {
        justify-items: center;
        align-items: center;
    }

    button {
    padding: 10px 100px;
    margin: 40px 0 5px;
}

    .container {
        
        padding: 5% 5%;
        width: 70%;
        margin: 40px;
        margin-bottom: 300px;
    }

    .num-circle {
        margin: 50px 2px 30px 2px;
        padding: 10px 15px;
    }
    

    .thank-you-container {
        padding: 5% 5%;
        margin: 40px;
        width: 70%;
    }
}

```
```js
function changeColor(element, backgroundColor) {
    element.style.backgroundColor = backgroundColor;
}
```

### Continued development

My focus on future projects is to have perfected my knowledge of JavaScript and know it fully well.

### Useful resources

- [Example resource 1](https://www.W3schools.com) - This helped me for CSS concepts. I really liked this pattern and will use it going forward.
- [Example resource 2](EasyTutorial YouTube Channel) - This is an amazing YouTube channel which helped me finally understand making a website responsive. I'd recommend it to anyone still learning this concept.
- [Example resource 3](https://www.mdn.com) - This is an amazing article which helped me finally understand some CSS concepts. I'd recommend it to anyone still learning this concept.

## Author

- Website - [creativeceptmedia](https://www.creativeceptnedia.com.ng/vtu)
- Frontend Mentor - [@creativeceptmedia](https://www.frontendmentor.io/profile/creativeceptmedia)
- Twitter - [@creativeceptmedia](https://www.twitter.com/creativeceptmedia)

## Acknowledgments

I thank God for this growth in knowledge
