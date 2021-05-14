# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Stats preview card component solution](#frontend-mentor---stats-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
  - [Author](#author)

## Overview

Good challenge to get you started with HTML/CSS Markup and component structure. 

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

<img src="https://oscarm.tinytake.com/media/101396c?filename=1620973619722_TinyTake14-05-2021-08-26-57_637565704188699319.png&sub_type=thumbnail_preview&type=attachment&width=406&height=789">


### Links

- Solution URL: [Solution URL](https://github.com/omiras/stats-preview-card-component-main)
- Live Site URL: [Live Site](https://omiras.github.io/stats-preview-card-component-main/)

## My process

1. Figure out all the main sections of the design and related components by __squaring__ and grouping them.

<img src="https://oscarm.tinytake.com/media/10138cf?filename=1620972474826_TinyTake14-05-2021-08-04-09_637565692740383927.png&sub_type=thumbnail_preview&type=attachment&width=313&height=799">

1. Write all the possible HTML according to the previous step. Try to get the most accurate design close to the requisites without a single line of CSS.
2. Add the images in the design. This one was added as background image.
3. Start by generally aligning elements without caring about margins and paddings. Write the minimal CSS to do so and start setting some classes in the HTML using BEM Methodology (not highly strict BEM)
4. Apply desired typography to the design by importing google fonts,  setting font family and font size as desired
5. Apply all the colors (font and background)
6. Set margins and paddings, using __em__ units
7. Leave the tricky parts for the end of the mobile design. In this case: the violet overlay over the main picture
8.  Once mobile design is finished, add a media query to adapt the design to desktop design.

### Built with

- CSS custom properties
- Inline-block for desktop design
- Mobile-first workflow


### What I learned

I learned how to markup a simple but yet interesting component with some tricky and interesting parts, such as setting an overlay or considering how to display the image on the left or right side, depending of the design.

### Continued development

* I was wrong by setting as <p> the stats of the card. They are not really paragraphs semantically speaking. This lead me to have to play too much with margins and paddings to accomplish the design. I would have used <div> instead
* I had to do some tricky tricks to display the image on the right for desktop design. This design is a really good candidate for a __flexbox__ design; with flow-reverse property to accomplish this feature. Yet, I wanted to stick to inline-block design for learning purposes.


## Author

- Website - [Oscar Miras](https://omiras.github.io/)
- Frontend Mentor - [@omiras](https://www.frontendmentor.io/profile/omiras)
