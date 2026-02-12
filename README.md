# QR code component web page

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

The main goal of this project was to build a QR code component and get it looking as close as the original reference, using provided style-guide.md file.

### Screenshots

<p style="text-align:center;">Pc and mobile versions of the webpage</p>
<div style="text-align:center;">
  <img src="./Qr_pc_version.png" width="600" alt="QR code PC">
  <img src="./Qr_mobile_version.png" width="224" alt="QR code Mobile">
</div>

### Links

- Solution URL: [Click](https://github.com/ilypr/QRcodeMentor)
- Live Site URL: [Click](https://qrcode-pr.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This project taught me the importance of optimizing a webpage first for phone users and then for PC users. It generally felt easier to optimize the webpage for the small screen first. Also, this project enhanced my understanding of the usage of parent and child elements in CSS code. I may have overwritten some parts of the code here and there, but it generally works without any problems, and the webpage doesn't produce any visual bugs when trying different resolutions of the screen. With all of that said, I also discovered information that you can remove standard CSS styles of the webpage by creating a pseudo class name (the \* at the beginning of the CSS code) that sets both padding and margin of the standard webpage style to 0. Besides the main project goal, I also played around with the footer of the HTML code and made it stick to the bottom of the webpage , and it would still be there if I or someone else tried to add extra text to the webpage.

```html
<h1>Some HTML code I'm proud of</h1>
```

```css
/* pseudo-license position (so It'd stick to the bottom of the webage) */
main {
  flex-grow: 1;
}

/* Removes standard padding and margin of the webpage */
* {
  margin: 0;
  padding: 0;
}

/* both (styling and positioning for the qr-code image) */
.QRcodeItself {
  display: flex;
  align-items: center;
  justify-content: center;
}

.QRcodeItself img {
  border-radius: 15px;
  width: 288px;
  height: 288px;
}
```
