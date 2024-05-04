# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

An introductory project to HTML & CSS by building a website with a QR code component. For beginners, it's ideal since the card layout does not shift so learners don't have to worry about building responsive layouts yet.

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/qr-code-component-HcH3MxYNHE)
- Live Site URL: [Add live site URL here](https://benhuynh003.github.io/QR-code-component/)

## My process

I approached the project by envisioning the layout as "boxes" - This made it easier for me to break the project to multiple elements and then to adjust them accordingly to the design provided by Frontend Mentor.

### Built with

- HTML/CSS
- CSS flex-box
- CSS media query

### What I learned

My key-takeaways from this project was the application of custom CSS properties & media query. 

```css
@media all and (max-width: 667px) {
    #QR-box {
        width: 85%;
        height: 75%;
    }
}

@media all and (min-width: 1440px) {
    #QR-box {
        width: 23%;
        height: 66%;
    }
}

@media all and (min-height: 1056px) {
    #QR-box {
        width: 23%;
        height: 50%;
    }
}

@media all and (min-width: 1920px) {
    #QR-box {
        width: 18%;
        height: 60%;
    }
}

@media all and (min-height: 1080px) {
    #QR-box {
        width: 18%;
        height: 50%;
    }
}
```
### Continued development

This is my first experience working with CSS media query hence I only accounted for four dimensions: 1920x1080, 1440x1056, 1440x800, 375x667. Future improvements will involve the consideration of all devices width and height.

## Author

- [@benhuynh003](https://www.frontendmentor.io/profile/benhuynh003)


