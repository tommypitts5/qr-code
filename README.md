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
- [Author](#author)

## Overview

### Screenshot

![](/images/Screenshot.png)
![](/images/ScreenshotMobile.png)

### Links

- Solution URL: [https://github.com/tommypitts5/qr-code](https://github.com/tommypitts5/qr-code)
- Live Site URL: [https://tommypitts5.github.io/qr-code/](https://tommypitts5.github.io/qr-code/)

## My process

This is the first project I've attempted on my own as part of my coding journey, up until this point I've only learned through tutorials and exercises set by instructors. Therefore, wanted to use this as an opportunity to practice the core CSS box model concepts, without resorting to grid/flexbox.

Decided to create a few basic containers for the HTML elements so that I could practice positioning via margin and padding.

### Built with

- HTML5 markup
- CSS

### What I learned

Decided to create a <div> container for the card, with the image and text content nested. Used CSS property position for the first time to center the card on the page. I haven't ever experimented with this before, usually jumping straight to flexbox.

```html
<div id="card">
  <img src="images/image-qr-code.png" alt="Frontend Mentor QR Code image" />
  <div id="text">
    <h1>Improve your front-end skills by building projects</h1>

    <p>
      Scan the QR code to visit Frontend Mentor and take your coding skills to
      the next level
    </p>
  </div>
</div>
```

```css
#card {
  background-color: white;
  border-radius: 20px;
  padding: 16px 16px 40px 16px;
  width: 320px;
  height: 499px;
  box-sizing: border-box;
  margin: auto;
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
}
```

### Continued development

Need to work on my CSS workflow, would like to solidify my knowledge of positioning concepts so that I can work methodically through a task, and spend less time and effort revisiting items.

## Author

- Frontend Mentor - [@tommypitts5](https://www.frontendmentor.io/profile/tommypitts5)
