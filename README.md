Four-card-feature-section-master README

# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). 
Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


![desktop-preview](https://user-images.githubusercontent.com/60264357/170023468-5d391f74-0069-4b63-a4e2-4600a23de5a2.jpg)


## Table of contents

- [Overview](#overview)

Here in this challenge, we have to build a webpage in which we have to insert a 
set of blocks assembled in a very special manner.These blocks have to be put 
together in a star shape.

  - [The challenge](#the-challenge)
The main difficulty in this challenge was to put together 4 blocks of same size in a spacial manner.
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)


For this project, at first, I have tought to implement 2 main containers: 
one for the headings and the main text and, a second one for the tables.
for the first container, I have chosen to use "Flex" for the display's property
and "grid" for the second container.
Looking at the design models given for this project, I have noticed the texts of the first container 
have to be put in the middle of the body while for the mobile design, the headings, 
main text and tables are like to be displayed in the same column but also in the center of the body.
Then, I changed my mind and came back to my first idea of implementing 2 grid-containers.
Therefore, for the first container, I have choosen "grid" as value for the display property.
Another issue I found tricky is that the two sentences of the heading had to have the same width.

Concerning how the tables would be displayed for the second container,
I have chosen to construct a grid of six columns and five rows for the desktop's version.
For the mobile's version,  the grid is composed of one column and four rows.
I have set a fixed widht and height for this second container according to how it would be displayed
on various devices. This would prevent the blocks to expend and have a wider or smaller size when 
reducing the surface of the screen.

And also to put the tables' logos at bottom right of these various tables. I just made a class in which
I defined they should be placed at the right side of these tables writting "Float: right".

  - [Built with](#built-with)

HTML and CSS

  - [What I learned](#what-i-learned)

I have learned many things about building grid-containers because it was really an issue to set these 
blocks in the required shape.

  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

MDN , w3schools.com and asking questions online about this challenge.

- [Author](#author)

Usanase Makala

- [Acknowledgments](#acknowledgments)

I personally thank anyone who responded to questions I have posted online regarding this 
project and I want also to thank personally FrontEndMentor for this opportunity of sharpening my 
coding skills.
