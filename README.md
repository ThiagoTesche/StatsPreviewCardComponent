# Frontend Mentor - Stats Preview Card Component

![Design preview for the stats preview card component](./design/my-design-desktop.jpg)

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [My design](#my-design)
    - [Desktop design](#desktop-desing)
    - [Mobile design](#mobile-design)
  - [Where to find everything](#where-to-find-everything)
  - [Link to site](#link-to-site)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

<br>

# Overview

## The challenge

The challenge is to build out this stats preview card component and get it looking as close to the design as possible.

<br>

## My design

# Desktop design

![](./design/my-design-desktop.jpg)

# Mobile design

![](./design/my-design-mobile.jpg)

## Where to find everything

-- The designs are inside the `/design` folder. You will find both a mobile and a desktop version of the design. 

-- The designs are in JPG static format. Using JPGs will mean that you'll need to use your best judgment for styles such as `font-size`, `padding` and `margin`. 

-- You will find all the required assets in the `/images` folder. The assets are already optimized.

-- The css's archives are in `scss` folder.

### Link to site

- Live Site URL: [stats-preview-card-component-tesche.netlify.app](https://stats-preview-card-component-tesche.netlify.app/)

<br>

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flex
- Grid
- Media Queries
- SCSS

<br>

### What I learned

Building this project, I learned about HTML semantics, CSS custom properties, Flexbox and Media Queries. I also learned how to use "@mixin", "@include" and ":root" in CSS and new way to write CSS. Other thing what I learned, it's about the overlay.  

```css
.right{
    background-image: url(/images/image-header-desktop.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    width: 50%;
    height: 100%;
    border-top-right-radius: 7px;
    border-bottom-right-radius: 7px;
    overflow: hidden;

    .overlay{
        width: 100%;
        height: 100%;
        background: var(--Soft-violet);
        overflow: hidden;
        z-index: 2;
        opacity: 0.5;
    }
}
```
<br>

<br>

## Author

- Author - Thiago Tesche
- Frontend Mentor - [@ThiagoTesche](https://www.frontendmentor.io/profile/ThiagoTesche)
- Instagram - [@thiago_tesche](https://www.instagram.com/thiago_tesche/)
- LinkedIn - [Thiago Tesche](https://www.linkedin.com/in/thiago-tesche-996b52213/)


<strong>Thank You!</strong>