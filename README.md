## Table of contents

- [Table of contents](#table-of-contents)
- [Overview](#overview)
  - [Objective](#objective)
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

### Objective
vUsers should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![1st Option Prev](./img-index/flex_pog.png.png)
![2nd Option Prev](./img-index/grid-ish.pngimg/big.png)
![3rd Option Prev](./img-index/navbar-img.pngimg/big.png)
![4th Option Prev](./img-index/Sussy.pngimg/big.png)


### Links

- Live Site URL: [Click me!](https://nostalgic-pasteur-18f054.netlify.app/index.html)

## My process

- Since it was pretty much from scratch I had to do a couple of drafts in paint, and get feedback from friends and parents
- Then I once again tried to find a way to add code snippets, and got it!
- Then the Styling was just a back and forth from html to css & sass

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- SASS 
- Fonts-used
  - [Raleway](https://fonts.googleapis.com/css2?family=Raleway) 
  - [Poppins](https://fonts.googleapis.com/css2?family=Poppins)

### What I learned

1. If you think you'll make a small project and there's no need to use SASS, you MUST use SASS
2. I finally know how to add code snippets in my pages!
3. 

**SASS**

- Got a better understanding on how to use flex on childrens
  
```scss
.container .seven > div { 
  &:nth-child(1) { order: 3; }
  &:nth-child(2) { order: 1; }
  &:nth-child(3) { order: 4; }
  &:nth-child(4) { order: 2; } 
}
```

- Got some practice on resizable elements and used them to make live examples of Flex

```css
/* this is a div that surrounds the div I want to resize */
.resize-it {
  border: 3px solid rgb(0, 14, 143);
  width: 96%;
  resize: horizontal;
  overflow: auto;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.15), 0 6px 20px 0 rgba(0, 0, 0, 0.12);
  }
.resize-it .container {
  border-radius: 7px;
}
```

- Saw how big a html whit html inside can become...

### Continued development

I want to keep working on:

- a
- Work whit more JS
- Understand better Media Queries

### Useful resources

- There's nothing here

## Author

- Twitter - [@8koi2](https://twitter.com/8koi2)
- Github - [Hachikoi-the-creator](https://github.com/Hachikoi-the-creator)

## Acknowledgments

I got the idea of the resize property from a Short of [Kevin Powell](https://www.youtube.com/kepowob) or [WebDevSimplfied](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw), can't remember lol


