## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Links
https://capylic1ous.github.io/social-link/

## My process

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox
- CSS Grids


### What I learned

I've learned a great deal about spacing with Flexbox and Grid. The project was going smoothly for me while I was centering the container. It was adding the elements inside of it when that became a nightmare. Originally I used CSS Grid to display the container. 

I'vd laid out all the elements (image, name, location, links) and gave them classes. There was too much space separating the image and headers from the link, while the links were also overlaping each other. This is my first real project fresh after working on the Flexbox and Grid courses on Codecademy so I was doing a good bit of back and forth referencing with my trial and error. In the end I got a better understanding on how grid-template-columns and grid-template-rows works. I played with those to align the elements top to bottom with 1 column.

Then I shrunk the container because I felt it was too big but then none of the elements shunk within the container. They got smaller but overlaped outside rather than staying inside the container. This also made me think about what if I needed to add more links, they would just continue to overlap the container, rather than the container growing with the added links. So I changed the display of the container from Grid to Flex, got rid of the other grid properties and everything snapped into place inside the container.

writing the width and height below allowed me to create more links while staying inside the container:

''' css
.container {
    width: 400px;
    height: auto;
}
'''
After styling the links some more, I went back to work on the fonts (setting the sizes, color and spacing)

Afterwards, I added the @media rules to make the site responsive for mobile devices.


### Continued development

I need continue working on my grid skills, understanding more of its syntaxes and how they work


### Useful resources

- (https://www.codecademy.com) - I went back to the CSS courses I recently completed on here to help me with the project. It offers free membership and hands on courses for web dev and other coding related fields.

## Author

- Frontend Mentor - [@Capylic1ous]https://www.frontendmentor.io/profile/Capylic1ous
