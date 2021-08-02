# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

## My process

1. HTML structure including text and images, tagging into headings, paragraphs and img tags.
2. Move the headings into a div named 'top-container' to seperate them from the other content.
3. Move the sub-headings, paragraphs and images for the boxes into four seperate divs, then place those four divs into a 3 seperate divs named "first" "middle" & "last" for y columns.
Add those column divs into a "card-container div to hold them and finally move that div into a 'middle-container' div.
4. Add my footer details into a div placed at the bottom within the body coding.
5. I started by typing out all of the selectors I was going to need. I then began to add my CSS code starting with the text and colors from the style guide provided. I added the google fonts into my text basket and copied the links into my html.
I then copied the CSS family-font code into my CSS selector fields.
6. I then moved onto text-align the main boxes and give padding to the top-container to bring the headings down the page.
7. I used the display tag to turn the card-container, the 3 holding containers and the four containers into flexboxes, which allowed me to position the contents easily.
8. I selected wrapping and direction: column for my 3 containers whcih allowed the boxes to center themselves. 
9. I added flex direction to the img tag to move the images from the left hand side to the 'flex-end' (right hand side) and added padding to them to bring them away from the edge. I also did this for the text in the box too.
10. My borders were added to the containers on top only to show the colored top border. Shadow was also added to the box only horizontally to mimic the example image, which was blurred to lighten the shadow too.
11. 

### Built with

-HTML
-CSS
-Flexbox

### What I learned

I struggled considerably to move my content and boxes to replicate where they sit on the sample image. This caused my to research and speak to a coder friend to figure out flexbox was the solution.
I looked into the flexbox on mdn and found that using a flexbox and justifying as well as aligning content would center my contents inside a flexbox. 
The wrapping and direction elements also became helpful when reading up the way they can wrap the content instead of squeezing or overflowing and the direction row or column helping to flow the contents a certain way.


  border-top: solid;
  border-top-color: hsl(180, 62%, 55%);
  width: 300px;
  height:208px;
  border-radius: 5px;
  background-color: white;
  box-shadow: 0 8px 30px -20px hsl(229, 6%, 66%);
  display: flex;
  flex-direction: column;
  margin: 20px;


### Continued development

Flexboxes are something I certainly want to perfect as I feel they provide the very easy ways to position and play with contents. This will help a lot moving forward with centering and positioning.

My code is very long winded to those who have probably had more experience so, I would like to carry on teaching myself shorthand coding and combining CSS selectors in the same line as this didnt work for me on this occassion.



### Useful resources

https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox - this helped me learn flexbox and how I can use it to create this particular challenge layout, was very helpful as mdn always is.

## Author

- Frontend Mentor - [@scott-the-coder] (https://www.frontendmentor.io/profile/Scott-the-coder)


