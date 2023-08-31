# Strawberry lovers

![Amiresponsive image](https://res.cloudinary.com/dmntcacug/image/upload/v1693427142/Amiresponsive_aeblsa.jpg)


Link to live website: [PP1 Strawberry Lovers](https://niclo1337.github.io/pp1-strawberry-lovers/index.html)

<hr>

## Table of contents


* [Testing](#testing)
    * [Automatic testing](#)
        * [Validator testing](#validator-testing)
        * [Lighthouse testing](#lighthouse-testing)
    * [Manual testing](#manual-testing)
        * [User goals](#user-goals)
        * [Features](#features)
        * [Browser](#browser)
        * [Devices](#devices)
    * [Bugs](#bugs)
        * [Solved bugs](#solved-bugs)
        * [Unfixed bugs](#unfixed-bugs)



## Testing

### Validator Testing

- HTML

- CSS
Validated through https://jigsaw.w3.org/css-validator/validator and passed
![Passed without errors](https://res.cloudinary.com/dmntcacug/image/upload/v1693422108/css-validator-pass_xthpbi.jpg)

### Lighthouse testing

Used lighthouse to test performance, accessibility, best practices and search engine optimization of the website. Each page was tested individually and had various scores.


#### Main page
Initial test result > result after optimization
<p align="left"><img src="https://res.cloudinary.com/dmntcacug/image/upload/v1693434928/lighthouse-home-before_rhmdin.jpg" alt="Initial test result main page" width="300"/></p>


#### Gallery page
Initial test result > result after optimization
<p align="left"><img src="https://res.cloudinary.com/dmntcacug/image/upload/v1693434928/lighthouse-gallery-before_afzzag.jpg" alt="Initial test result gallery" width="300"/></p>


#### About us page
Initial test result > result after optimization
<p align="left"><img src="https://res.cloudinary.com/dmntcacug/image/upload/v1693434928/lighthouse-about-before_nm4i67.jpg" alt="Initial test result about us" width="300"/></p>



#### Welcome page
Initial test result > result after optimization
<p align="left"><img src="https://res.cloudinary.com/dmntcacug/image/upload/v1693434928/lighthouse-welcome-before_zay8dg.jpg" alt="Initial test result welcome page" width="300"/></p>




#### Improvements
Different tactics were used to improve the lighthouse scores. 
- Converting images from jpg to webp format to drastically reduce the file size.
- 


#### Left to improve




### Manual testing
<hr>

### User goals

| User goal | How are they achived | 
| --- | --- | 
| Learn how to grow strawberries | Add content to main page about growing strawberries| 
| Learn new tips and tricks | Add more tips and tricks to main content|
| Find new and exiting recipes to try | Add recipe section to main page |
| Make new friends from all around the world | Add feature with option to join the community  | 


### Features

| Feature tested | Expected outcome | Pass / fail | 
| --- | --- | --- |
| **Header / navigation bar** | 
| Logo | Clicking takes user to Home page | --- |
| Home | Clicking takes user to Home page | --- |
| Gallery | Clicking takes user to Gallery page | --- 
| About us | Clicking takes user to About us page | --- |
| **Footer / Social media icons** | 
| Facebook | Opens Facebook in new tab | --- | 
| Twitter | Opens Twitter in new tab | --- | 
| Instagram | Opens Instagram in new tab | --- | 
| Youtube | Opens Youtube in new tab | --- | 
| **Internal links on main page** |
| Growing | Clicking takes user to Growing section | --- |
| Greenhouse | Clicking takes user to Greenhouse section | --- |
| Recipes | Clicking takes user to Recipes section | --- |
| **Other features** |
| Form submission | Clicking takes user to Welcome page  | --- |
| Play recipe video | Clicking on video starts it | --- |


### Browser
Website has been tested on Google chrome, Microsoft Edge and Safari.

| Feature tested \  On browser | Google Chrome | Microsoft Edge | Safari | 
| --- | --- | --- | --- |
| Click navigation links | --- | --- | --- |
| Click social media icons |  --- | --- | --- |
| Internal links on main page | --- | --- | --- |
| **Other features** |
| Form submission | --- | --- | --- |
| Play recipe video | --- | --- | --- |

### Devices
Manually tested on mobile device (Xiaomi 12), tablet (Samsung Galaxy tab S4) laptop and desktop computer.

| Devices | 
| --- | --- | --- | --- |
Mobile phone 



## Bugs

### Solved bugs

- Form submittion not working on deployed website, returned error code 405.
<br> Solution: Changed form method from POST to GET.
- Main content section colums "flexing apart" when increasing screen width.
<br> Solution: Increase max-width of columns combined with decrease max-width of flex container.




### Unfixed bugs

- HTML validation error from from invisible javascript above meta tag charset="UTF-8"

