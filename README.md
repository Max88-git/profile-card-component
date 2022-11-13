# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learnt](#what-i-learnt)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

View the optimal layout depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

Above is what you should see when you click on the link below.

### Links

- Solution URL: [Solution](https://github.com/Max88-git/profile-card-component)
- Live Site URL: [Live Site](https://max88-git.github.io/profile-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Animations

### What I learnt

I learnt a lot of layout techniques in this CSS challenge and how to structure your CSS properly. I discovered how to clip the bg-pattern-card to the card container using overflow: hidden which makes part of the content invisible. This only works for block elements with a specified height.
I also learnt how to use negative margin-top to pull the img element up and over the containing element.

Here are some code snippets I am proud of:

```css
.card {
  ...
	overflow: hidden;
  ...
}
.card-header {
	background-image: url(images/bg-pattern-card.svg);
	background-size: cover;
	height: 150px;
}
.img-holder {
	width: 110px;
	height: 110px;
	border-radius: 50%;
	border: 5px solid white;
	overflow: hidden;
	margin: -55px auto 20px auto;
}
```

### Useful resources

- [MDN CSS Overflow](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow) - This helped me for the card header pattern background. The content is clipped to fit the padding box, as the card had rounded edges but the pattern was extended on the top edges.
- [MDN Margin](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model) - This was useful in removing space between the img element and the card-body.

## Author

- Website - [Max Lockwood](https://www.maxlockwood.uk/)
- Frontend Mentor - [@Max88-git](https://www.frontendmentor.io/profile/Max88-git)
