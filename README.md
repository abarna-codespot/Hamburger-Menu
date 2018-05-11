# Hamburger Menu
A basic Hamburger Menu Animation using HTML, CSS and Javascript
![title-pic1](https://user-images.githubusercontent.com/39196039/39932952-30eb36c8-555f-11e8-8247-9258ac730722.jpg)

This repository contains code for creating a basic hamburger Menu Animation with few quick & easy steps. 
## The Approach Followed:
#### For converting the basic 3 lines to cross.
- Create a separate div section for 3 lines.
- Use "Change" class to animate them to cross sign.
- Use Toggle JS function to toggle between 3 lines and cross sign.
- Bring all the lines to a single line using transform.
- Then, rotate the first line and third line, 45deg, anti-clockwise & clock-wise respectively.
- Make the middle line disappear by setting opacity to 0.

#### For the background
- Create a div container below the menu created previously.
- Use "change-bg" class to animate this and mention the toggle functionality in javascript as well.
- Initially give the dimensions to this div as 0.
- Under "change-bg" give this the desired width & height.
- Mention both the menu & the background as position: absolute. This will place them on top of each other.
- Use z-index to mention the order.
- Finally, move the circle a little to left & top to get a curved desired background. 

