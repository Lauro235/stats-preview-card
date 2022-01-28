# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

[Mobile](.screenshots/stats-mobile.png)
[Desktop](.screenshots/stats-desktop.png)

Screenshots are made with the GoFullPage chrome extension.

### Links

- Solution URL: [Github](https://github.com/Lauro235/stats-preview-card)
- Live Site URL: [Codepen](https://codepen.io/Laurie312/pen/QWObQGB)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learnt that source sets are particularly important when image files sizes and quality are dramatically different. This helps to accommodate speed on mobile devices as well as high resolution on bigger screens. I decided not to implement srcsets as the files provided are not dramatically different. The deskstop picture is actually smaller than the mobile picture.

I learnt that when padding has 3 values the first relates to the top, the second to left and right and the third to the bottom.

I liked the effect of having a parent with a border radius and it's child, in our case a picture without a border radius. In this instance the effect only looks good when we add overflow: hidden; to the parent container.

I learnt that there are or seem to be limits to the clamp property. When a browser reaches above a certain screen size the clamp property seems to stop adjusting. It seems that most of the resizing is not done entirely in line with screen size, but more that it's done according to what will fit. I.e as soon as there is more space, it will grow. Meaning it will quickly take up the room you've allocated to it. My understanding might not be 100% correct and there could be other variables that were stopping the text from growing as expected, but I learnt that it's not as simple as I thought it would be to create a completely responsive text growing method.

To see how you can add code snippets, see below:

### Continued development

One thing I tried this time, but wasn't successful in was creating a live github page. As part of my personal development I want to reach out to an experienced github user, to ask them to help guide me through the process. I got an error on a couple of occasions and I'm not comfortable with the command line or have enough contextual knowledge to problem solve in those situations.

## Author

- My soon to be website - [Lorentz Bloom](https://www.hellouniverse.stream)
- Frontend Mentor - [@Lauro235](https://www.frontendmentor.io/profile/Lauro235)
- Twitter - [@Lauro235](https://twitter.com/Lauro235)

## Acknowledgments

I want to thank [@MargaretCodes](https://twitter.com/MargaretCodes) for her camaraderie and support. Also a thanks to Luke, Jerry and Chris for their continued support.
