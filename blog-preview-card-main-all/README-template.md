# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

Hello all, I'm Wes and this is my experience with the challenge. Generally it felt like a good challenge for my current level. Now that I've completed the project, the main thing I would like to improve is manipulating the elements inside a parent at a faster pace. I suspect investing time into learning flexbox and grid will improve this weakness.

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Links

https://blissonline.github.io/blog-preview-card/blog-preview-card-main-all/index.html

## My process

1. Download project files and pick a folder where to extract files
  -Open folder from your IDE, mine is Visual Studio Code

2. Get the jist of the project with the README.md
    -Organize notes on challenges you need to solve.
      -example: How do I make a hover FX that changes the text color

2. Go to github and make a repository 

3. In my IDE use git bash to link local project to the github repository 

4. Start to approach HTML. 
  -view the contents of the project like boxes. 
    -Start to count all the boxes and how many elements are in each box
      -I counted 1 box with 7 elements inside 

5. Write HTML
  - Take our knowledge of how many boxes and how many elemnts inside eaxh box start to make <div> tag(s)
    - I also make comments of every element inside the box to make it easier to read, also this makes it obvious what I need to do next

6. Link all photos with <img src="">
  -also use alt="" attribute to optimize accessibiiity

7. Write CSS
  -I like to start with colors
  -get parent element in proper position
    -use relative units for responsive design
  -get child elemnts in proper position 
    -relative units

8. Test responsive nature of website, shrink and expand, determine where and what the weakpoints are
  -make max or min width length for text that is too close to edges of the parent
  -make media queries if needed

9. Start to fine tweak and push to have the clean version of the desired website/app
  -There will probably be minor tweaks needed, make the adjustments 
    -A final tweak I needed was to properly align the icon photo with the author name, originally the icon image was too high
      -I used padding and margin manipulation to correct this
  - delete unused code and big empty space areas 

10. Create the README for your project
  -Leverage this reflection stage to put awareness on what you need to improve on
  -Organize it will so people can learn from your experience 

11. Push final version to github

12. Submit for feedback and learn from others who are further in the journey than you
  -Always be grateful for feedback 
  
13. Tackle the next step in your journey and keep improving 
  -Remember to be happy and celebrate your accomplishments and finished projects
  -You probably have an idea of where you need to improve at this point, start planning your next move 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

-margin collapse
  -when the top/bottom margins of elements collapse into one another 
-resize an image proportionally
  width: auto;
  height: 2em;
-hover selector with 
  -h1 :hover  {background-color: yellow;}
-shadow on box 
  -.fullDiv { box-shadow: 2px 2px black; }

### Continued development

-I had a inefficient approach to making child elements line up vertically
  -I'm hoping to find a more efficient way to layout child elements fast and in an organized fashion

-I think at this point I need to learn more about flexbox and grid 

## Author
Wes Laycock
- Website - <!--Coming soon-->

## Acknowledgments
YouTube
StackOverFlow

