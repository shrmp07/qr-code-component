# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

![](image.png), ![](image-1.png)


### Links

- Live Site URL: [Add live site URL here](https://github.com/Egbe-Fred/qr-code-component-main-HTML-and-CSS)

## My process
  The process was educating and I most say i learnt a lot while trying to build it the most important takeaway lesson was centering a <div> which was difficult to approached at first but with the help of Stark-Overflow and Google at the end of the day it was win win. 
### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- CSS Flex

### What I learned
I learnt how to center a div using the CSS grid. also the importance of a well structured HTML.

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html 
this was the structure of my HTML
<div class="background">
        <div class="card">
            <div class="codescan"></div>
            <div class="typo-div">
                <h3>Improve your front-end skills by building projects</h3>
                <p> Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
            </div>
        </div>
    </div>
````



```css
.background {
    display: grid;
    place-items: center;
    margin: 0 auto;
}

.card {
    display: flex;
    flex-direction: column;
    background-color: hsl(0, 0%, 100%);
    border-radius: 6%;
    min-height: 350px;
    width: 235px;
    padding: 15px;
    margin: 100px 0; 
    box-shadow: 30px;
}
```
