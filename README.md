# Frontend Mentor - Chat app CSS illustration solution

This is a solution to the [Chat app CSS illustration challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/chat-app-css-illustration-O5auMkFqY). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the component depending on their device's screen size

### Screenshot

![(image.png)]


### Links

- Solution URL: (https://www.frontendmentor.io/solutions/chat-app-css-SuAUFqjW8J)
- Live Site URL: (https://jp-mainieri.github.io/a004/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

```html
<section class="messages">
                <p class="user_msg">That sounds great. I'd be happy with that.</p>
                <p class="user_msg">Could you send over some pictures of your dog, please?</p>
                <div class="msg" id="msg3">
                    <img src="images/dog-image-1.jpg" alt="">
                    <img src="images/dog-image-2.jpg" alt="">
                    <img src="images/dog-image-3.jpg" alt="">
                    <p class="msg3Text">Here are a few pictures. She's a happy girl!</p>
                </div>
                <p class="msg3Text">Can you make it?</p>
                <p class="user_msg">She looks so happy! The time we discussed works. How long shall I take her out for?</p>
                <div class="tasks_">
                    <p>30 minute walk</p>
                    <span>$29</span>
                </div>
                <div class="tasks_">
                    <p>1 hour walk</p>
                    <span>$49</span>
                </div>
            </section>
```
```css
  .bg_gradient {
    width: 30%;
    height: 90vh;
    background-image: linear-gradient(to bottom, hsl(293, 100%, 63%), hsl(264, 100%, 61%));
    position: absolute;
    z-index: -1;
    border-radius: 0px 0px 1000px 1000px;
    
}

@media screen and (max-width: 1000px) {
    main {
        flex-wrap: wrap;
        align-items: center;
        justify-content: center;
        padding: 50px 10px 50px 10px;
    }

    aside {
        text-align: center;
    }
    
    .bg_gradient {
        width: 50%;
        height: 65vh;
    }
}
```