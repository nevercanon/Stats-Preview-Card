# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

## Screenshots

I will include screenshots of my project in my Github repository.

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I feel like one of the most significant things I learned was how to tint images with a color. I found an article online that said that you could use a background image with a linear gradient, but just using one color in the linear gradient. That was difficult for me to figure out and find a solution, and was very satisfying when it worked out.

I had difficulty with properly sizing the picture of the desktop version of the card. I tried to set the image's width to 50% so that it would be 50% of the width of the card container, but it wouldn't get big enough. Eventually I set the width to 100%, which was very close to what I was aiming for, though I didn't understand why I had to set the width that high since I only wanted it to be 50% of the card width. The only thing I could determine might have been the cause of this is that the main section and the div holding my image were siblings, with the card as their parent. So perhaps 50% of the card was already reserved for the main class contents. Can anyone explain to me what happened there? In the end, I never could get it to show the full picture and I don't understand why.

I also only ended up using the Inter font, and I didn't use the Lexend Deca font at all. I haven't been able to identify where it's supposed to be used in this project. Can anyone tell me where it's supposed to be used, and how to identify that kind of thing with similar fonts?

### Continued development

I'm going to work hard on practicing media queries in the future. They can be frustrating for me, but they're important to learn. I want to be able to write code for them that isn't as lengthy.

I'm also going to work on Mobile-first workflow in my projects from now on. I haven't been doing that on previous projects but I now understand that it's important.

I'm also planning on doing more Frontend Mentor projects to gain more skill in CSS, HTML, and JavaScript.

### Useful resources

- [Resource 1](https://css-tricks.com/tinted-images-multiple-backgrounds/) - This is the article that taught me how to tint the photo. It was very useful and I would never have thought of this method without assistance.
- [Resource 2](https://www.w3schools.com/css/css3_mediaqueries.asp) - This article helped me refresh my knowledge on media queries. I'm still not used to making them so reading basic tutorials is still helpful.

## Author

- Frontend Mentor - [@nevercanon](https://www.frontendmentor.io/profile/nevercanon)


## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**
