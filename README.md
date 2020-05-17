# Interactive Frontend Milestone Project - Travelverse

*Developer: Anthony Guillermo*

 - Project Brief 
 - Technologies
 - UXD
 - Deployment
 - Tests and Fixes
 - Media
 - Acknowledgements
 

## Project Brief

In this project I was tasked with building an interactive front-end site presenting useful information to users, using all the technologies learnt so far in this course.

The data was to be presented in way that helps users achieve their goals and and advance the site owners goals.

Build a website for users to choose their next holiday destination (Travelverse) mainly using technologies such as HTML, CSS, JavaScript and as on option jQuery or other jQuery libraries or external APIs. The project may be started using wireframes, as taught in the UX lesson.

Travelverse is a relatively new online business based in the Philippines opened 2 years ago. The following requirements were given by the travel agency after meeting with the client;

 - Display information about the different cities that are potential holiday destinations.
 - Allow users to select/search a destination and see a map with relevant attractions, accommodations and restaurants. 
 - Present the results in a way that is visually pleasing and user friendly.

## Technologies

 - HTML5
 - CSS3
 - JavaScript
 - jQuery
 - [Bootstrap v4.4.1](https://getbootstrap.com/)
- [Font Awesome v4.7.0](https://fontawesome.com/v4.7.0/)
- Google Maps API
- EmailJS

## UXD

**Strategy**

|Focus	|User Needs	|Business Objectives	|
|:------------:|:------------:|:------------:|
|Aims	|Interested in finding a holiday destination	|Increase clients	|
|	|Look at destinations and travel packages	|Retain clients	|
|Clients|Book travel package for myself/friends/family| Increase customer base|
|User objectives|View potential holiday destinations and packages|Gain more exposure
|	|View map of destinations with tourist spots|		|
|	|Read about destination and view pictures|		|
|	|Email/contact travel agency with questions or queries| 		|
|	|Find out about travel information|		|
|	|View social media sites|	|
|	|Subscribe to news letter|	|

**Scope**

|Focus	|Functional Specification	|Content Requirements	|
|:------------:|:------------:|:------------:|
|Features	|Home	|Information about site/choose a destination	|
|Future Features|Facilities	|Read about gym facilities	|
|	|Destination page	|View information/pics/map of destination|
|	|Account	|Sign in or sign up|
|	|Contact Us|Send question by email|
|	|Newsletter|Subscribe to newsletter|
|	|Travel Advice|View latest travel advice|
|	|Social Media|Access social media links|
|	|~~Bookings~~|~~View current bookings~~|
|	|~~Live chat~~|~~Chat live with an agent~~

**Structure**

|Focus	|Interaction Design	|Information Architecture	|
|:------------:|:------------:|:------------:|
|Information Structure	|How to navigate the site	|Navigational Structure (Tree/Dashboard)	|
|Groupings|Mobile- hamburger navigation|Home/Account/Contact|
|	|Desktop/Tablet - navbar|Home - Travel Agency info & Choose your destination (Baguio/Boracay/Manila)	|	
|	|	|Account - Sign in or sign up to personal account|
|	|	|Contact - Email queries or questions|
|	|	|Baguio/Boracay/Manila - Destination info/packages |

**Skeleton**

|Focus	|Interaction Design	|Navigational Design|		|
|:------------:|:------------:|:------------:|:------------:|
|Presentation of information|[See Wireframe](https://github.com/anthonybguillermo/frontend-project/blob/master/frontend-project/wireframe/wireframe-vipergym.pdf)|Home >|Baguio|
|User Navigation|Desktop/Tablet/Mobile - travel advice/social links in footer||Boracay|
|	|	|	|Manila	|
|	|	|Account|	|
|	|	|Contact	|	|

**Surface**

|Focus	|Visual Design	|
|:------------:|:------------:|
|Look of finished product|	|
|Colors and typography used|[Oxanium Font](https://fonts.googleapis.com/css?family=Oxanium&display=swap)	|
|	|#66b933	|
|	|#474140|

## Deployment

 - On project repo page on GitHub click on "Settings"
 - Scroll  down to "GitHub Pages"
 - Select master branch from drop down bar under "Sources"
 - Select "Save"
 - Project link: [Viper Gym](https://anthonybguillermo.github.io/frontend-project/)

## Tests and Fixes

HTML Validator Results
CSS Validator Results

**Mobile** 
Tested on Chrome mobile simulator

***Mobile Issue***
In facilities page was overlapping/blocking navigation bar

***Mobile Fix***
Adding a class in "Trainers" column to hide the text when on mobile.

> class="col-12 col-lg-3 d-none d-sm-block"

***Desktop/Tablet***
Tested on Chrome desktop and tablet simulator

***Desktop/Tablet Issue***
There was a gap between the the "Hero Image" on the Home page and the "3 Step Plan" section. 

***Desktop/Tablet Fix***
In "content-container" changed "margin-top" to "padding-top".

> .content-container {
padding-top: 75px;
padding-bottom: 75px;
}

## Media
The photos used in this project were taken from [pxhere.com](pxhere.com)



## Acknowledgements
Inspiration for this project was taken from [razer.com](razer.com) , [Mamba Sports Academy](https://mambasportsacademy.com/) and previous Code Institute Projects (Love Running, Resume and Whiskey Drop).