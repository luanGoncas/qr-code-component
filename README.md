# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

#### Desktop screenshot
![](./images/desktop_view.png)

#### Mobile screenshot
![](./images/s_mobile_view.png)

### Links

- Solution URL: [GitHub Repository](https://github.com/luanGoncas/qr-code-component)
- Live Site URL: [Frontend Mentor | QR Code Component](https://qr-code-component-peach-six.vercel.app)

## My process

- Setting CSS file and coloring the body background-color
- Display all elements on screen
- Put the typography properties
- Putting the elements on their respective classes
- Using viewport elements to find out correct margin and padding
- Using media queries for all default max-widths

### Built with

- Semantic HTML5 markup
- CSS custom properties
- [CSS media queries](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_media_queries/Using_media_queries)
- Mobile-first workflow

### What I learned

I learned to use responsiveness more effectively, rely less on Flexbox, and understand the differences in sizing across different devices.

```css
@media ((min-width: 320px) and (max-width: 375px)) {
    .main_card {
        padding: 0.5vh 0.5vw;
        margin: 12.5vh 15vw;
    }

    img {
        max-width: 65vw;
    }

    .main_text {
        margin: 0 5vw;
    }
}

@media ((min-width: 375px) and (max-width: 425px)) {
    .main_card {
        padding: 0.5vh 0.5vw;
        margin: 7.5vh 15vw;
    }

    img {
        max-width: 65vw;
    }

    .main_text {
        margin: 0 10vw;
    }
}

@media ((min-width: 425px) and (max-width: 768px)) {
    .main_card {
        padding: 0.75vh 0.5vw;
        margin: 7.5vh 16vw;
    }

    img {
        max-width: 60vw;
    }

    .main_text {
        margin: 0 12.5vw;
    }

    .scan_text {
        margin: 2vh 1vw;
    }
}

@media ((min-width: 768px) and (max-width: 1024px)) {
    .main_card {
        padding: 0.75vh 0.5vw;
        margin: 7.5vh 35vw;
    }

    img {
        max-width: 25vw;
    }

    .main_text {
        margin: 0 2vw;
    }

    .scan_text {
        margin: 2vh 0;
    }
}
```

## Author

- Website - [Luan Santos Gonçalves](https://www.linkedin.com/in/luangoncas/)
- Frontend Mentor - [@luanGoncas](https://www.frontendmentor.io/profile/luanGoncas)
