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
  - [Continued development](#continued-development)


## Overview

### The challenge

- View the optimal layout for the site depending on their device's screen size
- Build the project as accurately as possible according to the design specifications provided

### Screenshot

![](./Solution.png)

### Links

- Live Site URL: https://aidenm99.github.io/Profile-Card-Project/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

- How to use and modify multiple background images 

```css
background-image:url("../images/bg-pattern-top.svg"), url("../images/bg-pattern-bottom.svg");
background-repeat: no-repeat;
background-position: -100px -300px, 900px 500px;
```

- Using negative values to manipulate content
```css
.victor {
  margin-top:-50px;
}
```

- Use of the !important tag
```css
.statistics {
  color:hsl(229, 23%, 23%) !important;
  letter-spacing: normal; !important;
}
```

- How to use flexbox to position content 

```css
.container {
  height:100vh;
  display:flex;
  flex-direction:column;
  text-align:center;
  align-items:center;
  justify-content: center;
}
```

- Letter spacing

```css
.meta {
  letter-spacing: 2px;
}
```

### Continued development

I plan to continue using flexbox so that I can become better at it in the future. This was my first experience in using it so therefore I'm not completely satisfied with 
my current level of understanding.


