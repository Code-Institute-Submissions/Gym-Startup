# NU Life Gym website

## Milestone one project for code institute User Centric Frontend Development

# UX

## Project Goals

The website I have created is based upon a ficticious independent family orientated gym looking to create an online presence to help generate more memberships and show the world who they are.
The website focuses on a family friendly environment, helping families stay healthy together.
As it is a family orientated gym I have envisioned each age group of a typical family to highlight what they may expect or would want from a gym of this nature.

### Business Goals

* To create a new website to generate an online presence to increase gym memberships
* Provide a positive user experience that offers a user friendly approach providing all the information about the gym and its facilities
* As the gym provides classes give brief descriptions of these and also a schedule of times and days they take place.
* Provide location and contact details, including a contact form so that users and send in their details so we can contact them directly to then attend and sign up to the gym.
* Show clear and concise pricing information and any additional pricing options.
* Use a well presented branded and coloured scheme across all pages.


### User Goals

* A clear and easy to use site giving a positive user experience
* A trustworthy and safe place to go, that may have possible existing member tesitmonials
* A clear membership plan with pricing information
* What facilitate are availble with the use of some imagery to show these
* Where the gym is located with some contact information, some form of contact to show interest in joining the gym
* Information on child care areas if this is available
* See what is availble for all family memebers if I were to join

### Returning User 

* To see the latest news and what upcoming events are going to take place
* Any new classes or groups starting up

# User Stories
### The parent

* As an actor playing the role of a parent, I would want a safe and trusting environment for the whole of my family that also offers a good value for money for the family membership.
* As it is a family membership I would like to see what is available for each member of my family making sure they are able to make use of the facilities.
* I also have a very young child who may not be able to use the facilities and I cannot put them in child care, does the gym offer some sort of cresh/child care while the older members of the family can use the gym?
* Are they exercise classes available and are they open to all ages? I would like to do classes so I would like to see a schedule to to see I can attend these.
* Does the gym offer a personal trainer as part of the package or is there an option to add this to help with a routine. If so can they offer a healthy eating plan.
* What time is the gym open and can I only go at certain times as I work full time and may be limited to times I can go. I would also like to know where it is based so I dont have to travel too far.

### The Child (8+)

* As an actor playing the role of a yound child, I would want to know if there are any fun groups or classes I can attend to exercise and learn to be healthy, preferrably with people of a simular age.
* Is there a pool at the gym as I enjoy swimming and some of my friends may not be able to swim yet so are there swimming lessons available?
* Can I be taught and shown how to use the gym equipment as I have never been in a gym before

### The very Young Child, Toddler, even baby

* Thinking on this age group who may be too young to safely use the facilities, they may require other needs while the other family member do.
* Will child care be availble as part of the gym membership and will the staff be trained and trusting
* If there is a pool, maybe there are lessons and even a parents and Toddler only session
* A supervised cresh/play area for the younger children to be while the gym is used by the parents and older family members.

### Ederly (60+)

* As an actor playing this age group I may prefer to only use the gym earlier in the day and with a group of people who are my age. Is this an option?
* I may want to try a class instead of using the equipment, will there be one I can attend that may be slower and more in tune with someone my age
* I may need some help with accessabilty for parking, entry or inside the changing rooms when showering. Do you facilitate this?
* Are there good and well trained medical practices by the staff on site should anything untoward happen?

# Design

* Color Scheme - The two main colours for the site are green and white. This will be used across all pages
* Typography - Not decided just yet
* Imagery - Imagery is important. The large, background hero image is designed to be striking and catch the user's attention, while trying to enforce the family feel of the website.
* Responsivness - The site should be responsive on all common devices

## Layout

### Pages

#### The website will be made up of four pages total:
Each page will have the same framework which will contain a nav bar which includes links to each page and a footer which will contain copyrite information and social media links which will open up in a new tab.

* Home (Page 1) - A home page which will use a hero background image. A general why us and reasons for joining the gym.
* Classes (Page 2) - A page which will contain information on classes and a day to day schedule of the classes that currently take place which will include time and dates.
* Gym information ( Page 3) - To provide more information including membership details, pricing, extra facilities included and a small gallery to provide users imagery to equiptment and classes.
* Contact (page 4) - A page to give the user all the relevant contact information and a form to fill in to contact the gym.

### Wireframe

* [Home Page](https://github.com/Leemac79/Gym-Startup/blob/master/assets/wireframes/home-screen.png)
* [Classes Page](https://github.com/Leemac79/Gym-Startup/blob/master/assets/wireframes/classes-screen.png)
* [Facilities Page](https://github.com/Leemac79/Gym-Startup/blob/master/assets/wireframes/facilities-screen.png)

# Features

## Existing Features

* A fixed navbar that is always visable on the page even when you are scrolled down
* On the home page a few quick links to pages after the user reads the short information of text. These are links within buttons that stand out on the page.
* On the classes page a schedule built in from html code showing classes and times. These will be fully responsive to look visually appealing on each device.
* On the facilities page there is a contact form for users to register their interest in joining the gym. This is fully styled including the submit button.

## Features Left to Implement in the future

* An ability to log into the site to access other areas including the ability to book onto a class via the schedule page.

# Technologies Used

## Languages
* HTML
* CSS
* Bootstrap

### Frameworks, Libraries & Programs Used

* Bootstrap 4.4.1:
Bootstrap was used to assist with the responsiveness and styling of the website.

* Hover.css:
Hover.css was used on the Social Media icons in the footer to add the float transition while being hovered over.

* Google Fonts:
Google fonts were used to import the 'Titillium Web' font into the style.css file which is used on all pages throughout the project.

* Font Awesome:
Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.

* jQuery:
jQuery came with Bootstrap to make the navbar responsive but was also used for the smooth scroll function in JavaScript.

* Git:
Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.

* GitHub:
GitHub is used to store the projects code after being pushed from Git.

* Balsamiq:
Baslsamiq was used to create the wireframes during the design process.

# Testing &  Validation

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of this project to ensure there were no syntax errors on each page.

* https://validator.w3.org/
* https://jigsaw.w3.org/css-validator/


Using the above I acheived no errors in my pages for index.html and classes.html. I had errors in my facilities-pricing.html of which were rectified to give a successful no errors page.

The fixed error was in regards to the wrong field type being used in my form for the telephone section. I had used phone rather than tel.

I have thoroughly tested this website and was unable to find any broken links within it. I have also tried to submit blank contact forms and incorrectly filled out fields to give
an error message on each field to show that the required attribute within my form is working as it should. I also made sure that it was filled out correctly to make sure the submit button
open up a new tab with the code institue successful page.

### Devices Tested

* Samsung Galaxy S6 S7 S8 S9
* iPhone X/6/7/8
* Pixel 2 / 2XL
* Desktop
* iPad

### Browsers Tested

* Microsoft Edge
* Firefox
* Chrome
* Safari

# Bugs and fixes

* issue with responsive elements on my home page regarding the hero image not resizing 
for mobile viewports after multiple testing using the developer tools on chrome this was due to the size of my image used.
I resized the image using https://www.adobe.com/uk/photoshop/online/resize-image.html This then resolved my issue.

* issues with the schedule page to display correctly on the different viewports. Experimenting with
various col- options to achieve the desired display across all platforms.

* issues with the lower part of the facilities-pricing page in regards to getting to be responsive over various viewports.
The page would look fine on desktop and ipad screen sizes, however the page would not display correctly on mobile. The sizes
would scale too small making the page un-useable. After using the development tool on chrome I discovered my CSS width value was
incorrect. I also had to adjust the -col values to get the desired appearence.

## Design and evolution of the web page

After thinking about content and the flow of information to a new user I have decided against having 
four pages. The final page was going to be a contact page but I have not decided that this should be 
merged into the membership page. The reason for this is that not only a large space would be wasted on
the last page, but as a user would be on the membership information page. There would be a higher chance
of a user filing out a form while they are on the membership information page than if they had to go to
page to do this.

# Deployment
My website is currently deployed on Github Pages - https://

I was able to deploy the website here by going to my repository in which all the files are saved, clicking on settings at the top and
scrolling down to the heading GitHub Pages. Underneath the heading there is a source and I chose master branch from the dropdown which
allows you to host the website on GitHub Pages.

# Acknowledgements

* creating the contact form with style
  https://www.w3schools.com/howto/howto_css_contact_form.asp

* using and learning about flexbox styling for content on my membership page
https://flexboxfroggy.com/

* Images within the website were attained from the following sources
  * https://www.freepik.com/
  * https://pixabay.com/

* The images I used were then put together using my own Adobe Creative Suite to create the banners for my home and classes pages. The images used were from the above.

* The Code Institute https://codeinstitute.net/

* Bootstrap https://getbootstrap.com/docs/5.0/getting-started/introduction/ for creating various parts of my webpage to help the layout and responsiveness.
