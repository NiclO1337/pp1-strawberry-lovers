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

### Automatic testing

### Validator Testing

- HTML
Validated through https://validator.w3.org/#validate_by_input and passed
![Passed without errors](https://res.cloudinary.com/dmntcacug/image/upload/v1693510294/html-validator-pass_lwfaja.jpg)

- CSS
Validated through https://jigsaw.w3.org/css-validator/validator and passed
![Passed without errors](https://res.cloudinary.com/dmntcacug/image/upload/v1693422108/css-validator-pass_xthpbi.jpg)

### Lighthouse testing

Used lighthouse to test performance, accessibility, best practices, and search engine optimization of the website. Each page was tested individually and had various scores.


#### Main page
Initial test result > result after optimization
<p align="left"><img src="https://res.cloudinary.com/dmntcacug/image/upload/v1693492117/lighthouse-home-before-after_pyymmp.jpg" alt="Initial test result main page" width="300"/></p>


#### Gallery page
Initial test result > result after optimization
<p align="left"><img src="https://res.cloudinary.com/dmntcacug/image/upload/v1693492120/lighthouse-gallery-before-after_ff9xan.jpg" alt="Initial test result gallery" width="300"/></p>


#### About us page
Initial test result > result after optimization
<p align="left"><img src="https://res.cloudinary.com/dmntcacug/image/upload/v1693492119/lighthouse-about-before-after_np45qx.jpg" alt="Initial test result about us" width="300"/></p>



#### Welcome page
Initial test result > result after optimization
<p align="left"><img src="https://res.cloudinary.com/dmntcacug/image/upload/v1693492118/lighthouse-welcome-before-after_vvjnlz.jpg" alt="Initial test result welcome page" width="300"/></p>




#### Improvements
Different tactics were used to improve the lighthouse scores. 
- Converting images from jpg to webp format to drastically reduce the file size.



#### Left to improve
- Optimizing embedded YouTube video and other assets with
"Lazy load third-party resources with facades".





## Manual testing

### User goals

| User goal | How are they achived | 
| --- | --- | 
| Learn how to grow strawberries | Add content to main page about growing strawberries| 
| Learn new tips and tricks | Add more tips and tricks to main content|
| Find new and exciting recipes to try | Add recipe section to main page |
| Make new friends from all around the world | Add feature with option to join the community  | 


### Features

| Feature tested | Expected outcome | Pass / fail | 
| --- | --- | --- |
| **Header / navigation bar** | 
| Logo | Clicking takes the user to the Home page | Pass |
| Home | Clicking takes the user to the Home page | Pass |
| Gallery | Clicking takes the user to the Gallery page | Pass  |
| About us | Clicking takes the user to the About us page | Pass |
| **Footer / Social media icons** | 
| Facebook | Opens Facebook in new tab | Pass | 
| Twitter | Opens Twitter in new tab | Pass | 
| Instagram | Opens Instagram in new tab | Pass | 
| Youtube | Opens Youtube in new tab | Pass | 
| **Internal links on main page** |
| Growing | Clicking takes the user to the Growing section | Pass |
| Greenhouse | Clicking takes the user to the Greenhouse section | Pass |
| Recipes | Clicking takes the user to the Recipes section | Pass |
| **Other features** |
| Form submission | Clicking takes the user to the Welcome page  | Pass |
| Play recipe video | Clicking on video starts it | Pass |


### Browser
Website has been tested on Google Chrome, Microsoft Edge, Safari, and Samsung Internet Browser.

| Feature tested \  On browser | Google Chrome | Microsoft Edge | Safari | Samsung Internet  |
| --- | --- | --- | --- | --- |
| Click navigation links | Pass | Pass | --- | --- |
| Click social media icons |  Pass | Pass | --- | --- |
| Internal links on main page | Pass | Pass | --- | --- |
| **Other features** |
| Form submission | Pass | Pass | --- | --- |
| Play recipe video | Pass | Pass | --- | --- |

### Devices
Manually tested on mobile device (Xiaomi 12), tablet (Samsung Galaxy tab S4) laptop, and desktop computer.

| Devices | Expected outcome / responsive | Achived |
| --- | --- | --- | 
| Mobile (Xiaomi 12) | Looks as intended on this small screen size | Yes |
| Tablet (Galaxy tab S4) | Looks as intended on this screen size | Yes |
| Laptop (1366x768px) | Looks as intended on medium size screen | Yes |
| Desktop (1920x1080px) | Looks as intended on big size screen | Yes |

The desktop computer also tested with Chrome developer tools from 280 px wide screen up to 1920 px.
Several media queries were created to make each feature responsive on different screen sizes. All testing was made on up-to-date browsers. 



## Bugs

### Solved bugs

- Form submission not working on the deployed website, returned error code 405.
<br> Solution: Changed form method from POST to GET.
- Main content section columns "flexing apart" when increasing screen width.
<br> Solution: Increase max-width of columns combined with decrease max-width of flex container.
- The about page did not look as intended on a tablet in a horizontal layout. But not visible on Chrome developer tools.
<br>Solution: Forced input fields to be smaller on 450px screen and then back to auto width on 1200px screen.





### Unfixed bugs

- HTML validation error from from invisible JavaScript above meta tag charset="UTF-8".
More info after research and contact with tutor support: My computer adds JavaScript to the source code of the deployed website. This is not shown for other people.
Temporary solution: Validate from written code instead of source code.

