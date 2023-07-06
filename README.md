# VAMPIRES
![Website testing for responsiveness](assets/images/website_responsive.PNG)
This website is a brief history about Vampires, how in time our perspective changed about them in our culture: books, movies and etc.
The aim of this website is to  present my skills on HTML and CSS that i have acquired on Code Institute "Full Stack Development" course.

Link to live page: https://tomosius.github.io/Vampyre/

## Table of contents
- [VAMPIRES](#vampires)
  - [Table of contents](#table-of-contents)
  - [User Experience (UX)](#user-experience-ux)
    - [Website Aim](#website-aim)
    - [Stories](#stories)
  - [Design](#design)
    - [Color Cheme](#color-cheme)
    - [Images](#images)
  - [Features](#features)
    - [General Features](#general-features)
    - [Accessibility](#accessibility)



## User Experience (UX)
### Website Aim
* This website is to represent world of "Vampires"
* Show how our perspective about them changed in timeline
* Give reader access to contact website designer
### Stories
* Brief history about Dracula
* First movie about Vampires
* Changing perspective about vampires
* Vampires in modern art
## Design
### Color Cheme
* Website is based on these colors:
  - Blood RGB(136,8,8)
  - Black
  - White
  - Smoked-White (les vibrant white)
  
### Images
* All images are used from Internet with common or free user rights

## Features
### General Features
* background: linear-gradient(to bottom, white, #880808):<br>
White color is changing to blood from top towards bottom of page, for this i have implemented
* article:nth-child(odd) > img <br>
aligning all articles images that are odd to be floating to right
* article:nth-child(even) > img<br>
aligning all articles images that are even to be floating to left
* @media screen and (max-width: 600px)<br>
Settings for website when used on small screen with resolution 600 pix and below
* Page Contact has inline styling as on some screens footer gets higher then bottom, as page is prety tiny, for this i used: style="height: 100vh;"
* Navigation bar has links to all pages: Home, Brief History, Contact
* Footer has links to Personal LinkedIn, Source Code and this README.md
* When hovering mouse above an Element, color changes
* Main page Intro text is placed on image with lighter background
* Same page on smaller screen sizes, that text moves above the picture
### Accessibility
* all links have 'aria-label' to ensure readability of the website
* all images have 'alt' attributes
* Headings elements 'h1', 'h2', 'h3' have been applied to convey structure



<!-- 
## User Experience (UX)
### Website Aim
* This website is to represent world of "Vampires"
* Show how our perspective about them changed in timeline
* Give reader access to contact website designer
### Stories
* Brief history about Dracula
* First movie about Vampires
* Changing perspective about vampires
* Vampires in modern art
## Design
### Color Cheme
* Website is based on these colors:
  - Blood RGB(136,8,8)
  - Black
  - White
  - Smoked-White (les vibrant white)
  
### Images
* All images are used from Internet with common or free user rights

## Features
### General Features
* background: linear-gradient(to bottom, white, #880808):<br>
White color is changing to blood from top towards bottom of page, for this i have implemented
* article:nth-child(odd) > img <br>
aligning all articles images that are odd to be floating to right
* article:nth-child(even) > img<br>
aligning all articles images that are even to be floating to left
* @media screen and (max-width: 600px)<br>
Settings for website when used on small screen with resolution 600 pix and below
* Page Contact has inline styling as on some screens footer gets higher then bottom, as page is prety tiny, for this i used: style="height: 100vh;"
* Navigation bar has links to all pages: Home, Brief History, Contact
* Footer has links to Personal LinkedIn, Source Code and this README.md
* When hovering mouse above an Element, color changes
* Main page Intro text is placed on image with lighter background
* Same page on smaller screen sizes, that text moves above the picture
### Accessibility
* all links have 'aria-label' to ensure readability of the website
* all images have 'alt' attributes
* Headings elements 'h1', 'h2', 'h3' have been applied to convey structure



***
## User Experience (UX)
### Website Aim
* This website is to represent world of "Vampires"
* Show how our perspective about them changed in timeline
* Give reader access to contact website designer
### Stories
* Brief history about Dracula
* First movie about Vampires
* Changing perspective about vampires
* Vampires in modern art
## Design
### Color Cheme
* Website is based on these colors:
  - Blood RGB(136,8,8)
  - Black
  - White
  - Smoked-White (les vibrant white)
  
### Images
* All images are used from Internet with common or free user rights

## Features
### General Features
* All website (all pages) have the same background style:
    








   - [Images](#images)
1. [Features](#features)
   - [General Features](#general-features)
   - [Accessibility](#accessibility)
2. [Testing](#testing)
   - [Responsiveness](#responsiveness)
   - [Compatibility](#compatibility)
   - [W3C validation HTML](#w3c-validation-html)
   - [W3C validation CSS](#w3c-validation-css)
   - [404 page](#404-page)
3. [Technologies](#technologies)
   - [Languages Used](#anguages-used)
   - [Bootstrapping](#bootstrapping)
4. [Deployment](#deployment)
   - [Tools Used](#tools-used)
   - [GitHub Pages](#github-pages)
5. [Acknowledgements](#acknowledgements)
   - [Teaching](#teaching)
   - [Support](#support)
   - [Thanks To](#thanks-to)











## Main Page
- I have chosen Bran Castle as the main picture, as most of people when we thing about vampires, first thing that springs to mind is Dracula, and everyone knows, that he originates from Bran Castle, Transylvania
- Also i have implemented some text over that picture to show how text can be placed above image with some background, that is in different color and semi-transparent, so it is easier to read it.
- Whole website has 2 colors: white color transitions to blood vertically.
- If error accurs on website (it is not loading), it automatically redirectts to 404 page.

## Brief History
- On this page i have created 4 articles each consisting of image and text
- All images are automatically floating to left or right, depending on what article they are (odd or even). This makes in certain way like a boxed style website, that is easy to read. 
- I have used Justify alignment for text

## Contact
- On this page i have created form, where reader (or website visitor) can contact if want to, some fields are required, otherwise it will not be possible to submit form:
    1. First Name - Required
    2. Last Name
    3. Email address - Required
    4. Message - Required. For message field i have used textbox function, so field is bigger for content.
    5. Button - Send Message
- After message is submitted, you will be redirected to another page, where it shows that message was received

## Navigation
- I have created 3 navigation buttons:
    1. Home Page
    2. Brief History
    3. Contact
- All navigation are links to specific website files with hidden decorations and list marks.
- navigation links are presented in black color, but when mouse is above it, they become red color to show that website is responsive.

## Footer
- Footer is located at the bottom of website and i have made its background black, so it stands out
- Footer contains links:
    1. My personal LinkedIn Profile
    2. Source code of this project
    3. About - small description about this project
- Each link has 2 elements:
 1.  Icon
 2.  Link Name
 - Each link will redirect you to specific website (according to link name) and will open in new tab.

## Languages Used:
- ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
- ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

## Fonts and colours:
- I have implemented 2 different fonts:
  1. Abbadon - this font is stored locally on server
   2. Didact Gothic - bootstrapped from Google Fonts
- Website is based on few colors:
    1. White
    2. Black
    3. Blood RGB (136, 8, 8)
    4. Whitesmoke - i used this color for text inline with black background

## Additional information:

- All content was written by myself, sorry for any grammar mistakes, as English is not my native language
- Imaged are used from internet with Common licensing, so they are free to be used.
- Guidance, teaching and lessons are from [Code Institute](https://codeinstitute.net)
- Advises were taken from my mentor Marcel (Code Institute) -->