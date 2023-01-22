# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![Screenshot](/screenshot.png)

### Links

- Solution URL: [My Solution](https://www.frontendmentor.io/solutions/profile-card-component-hunbAHRErw)
- Live Site URL: [GitHub Pages](https://delanohendrix.github.io/Profile-Card-Component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Initially to position the profile image I used top, but later learned it would keep the original position of the element as well. This then made all following elements lower down than intended. To counteract this I learned that using a negative margin created the intended effect without retaining the original position as well.

```css
.profile__image {
  display: flex;
  position: relative;
  width: 95px;
  height: 95px;
  border-radius: 50%;
  border: 5px solid white;
  margin: -55px auto 0;
}
```

### Useful resources

- [CSS Reference](https://cssreference.io/) - This site helped me by refreshing me on the usage of various css attributes and properties.

## Author

- Frontend Mentor - [@delanohendrix](https://www.frontendmentor.io/profile/delanohendrix)
