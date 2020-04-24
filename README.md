# Saitama Dainingu | A Private Dining Experience
Static Front End Website - Code Institute Milestone Project 1

This project is a website that contains three pages: a landing, about and galery page. The purpose of this website is to attract and inform new customers by a simple, but strong, visual design. The website contains functional information, such as a contact form and a downloadable menu, as well as an image gallery and a background story to balance the purpose of the website.

![alt text][logo]

[logo]: https://raw.githubusercontent.com/MatthewYong/milestone-project-1/master/readme/images/image-landingpage-device.png

## UX
To understand what kind of website we need to deliver to the client, we need to define the development process of each stage. This can be done by analysing and breaking down the development process of the project into five planes:

### 1. Strategy Plane
The strategy plane defines the business objective and the user needs (goals). The goals for this project are defined as:

| Business Goal | Customer Goals |
| :------------- | :---------- |
|  As an owner of the restaurant I want the website to: | As a customer I want to:  |       
| 1. Be eye-catching and attract customers by using a simple and unique design  | 1. Contact the restaurant for a reservation or more information | 
| 2. Have the ability to contact the owner or make a reservation through a form | 2. To be more familiar with the chef’s cooking and history of this restaurant 
| 3. Increase marketing by having social media links on the website | 3. See photos of chef's dishes | 
| 4. Send newsletters for latest update | 4. See the price of the menu and download a PDF version of the menu  | 
| 5. To have the ability to accept a payment for a reservation  | 5. Make a reservation through an agenda | 


### 2. Scope Plane
The scope plane defines the features that are and are not possible to include in the website. This will be further in detail explained in the next chapter. A summary of the included and not included features are:

| Features (included) | Future features (not included)|
| :------------- | :---------- |
|1. Navigation menu bar: Home, About, Gallery, Contact | 1. Make a reservation through an agenda|
|2. Hero images | 2. Accept a payment for a reservation|
|3. Reseservation information and a downloadable PDF menu|
|4. Location of the restaurant through Google maps | 
|5. Footer with copyright and social media links|  
|6. Photo gallery | 
|7. About page | 
|8. Contact section | 


### 3. Structure Plane
The structure plane defines the information architecture and interaction design with the user. The following definitions has been used for this website:
- First impression of the website needs to be simple and clear as possible
- No more than three clicks are required for the user to reach a page
- The type of information architecture that will be used is the ‘Hierarchical Tree’, see image below

![alt text][hierarchy]

[hierarchy]: https://raw.githubusercontent.com/MatthewYong/milestone-project-1/master/readme/images/image-structure-plane-hierarchy.png


### 4. Skeleton Plane
The skeleton plane defines a basic visual design of the website through, for example, a wireframe. The wireframes for this project are made with Balsamiq can be downloaded from the following link:

- [Wireframe - Desktop version](https://github.com/MatthewYong/milestone-project-1/raw/master/readme/wireframes/Wireframe%20-%20Desktop%20Version.pdf)
- [Wireframe - Tablet version](https://github.com/MatthewYong/milestone-project-1/raw/master/readme/wireframes/Wireframe%20-%20Tablet%20Version.pdf)
- [Wireframe - Mobile version](https://github.com/MatthewYong/milestone-project-1/raw/master/readme/wireframes/Wireframe%20-%20Mobile%20Version.pdf)

Below you can find an example of a wireframe of the landing page

![alt text][wireframe]

[wireframe]: https://raw.githubusercontent.com/MatthewYong/milestone-project-1/master/readme/images/image-example-wireframe.png


### 5. Surface Plane
The surface plane is the final plane in the design process and defines the appearance of the website. This website needs to attract customers, but also needs to reflect the calmness during the dining experience. The following design style has been used:

| Design Style | Design Choice|
| :------------- | :---------- |
Font: Noto Serif JP | A Japanese Google font that reflects the theme of the business|
Text color: #fde3a7 | A bright yellow color that represents wealth and success in Japan|
Background color: 2A2A2A | A calm background that represent the dining experience|
Contrast ratio: 11.42 | A high ratio to express the visibility of the text (source: contrast-ratio.com)|


## Features
A summary of the features were described in the scope plane. This chapter will explain what the purpose is of each feature and what will left to implement for the future.

### Existing Features
| Features (included) |Explanation|
| :------------- | :---------- |
|1. Navigation menu bar: Home, About, Gallery, Contact | 1. The menu bar allows users to swiftly navigate through the entire website and indicates which page they are currently on|
|2. Hero images | 2. The hero image attracts users to stay on the website and allows users to make reservation with a direct link to the contact form
|3. Reseservation information and a downloadable PDF menu| The information section let users know what to expect and allows users to open a link to menu which can be downloaded as well.|
|4. Location of the restaurant through Google maps | The location of the restaurant allows users to plan their visit using the familiarity of Google Maps|
|5. Footer with copyright and social media links| The footer allows users to receive the latest updates by subscribing to the restaurant's pages|
|6. Photo gallery | The photo gallery allows users to be more familiar with the chef's dishes|
|7. About page | The about section allows users to be more familiar with the history of the owner |
|8. Contact section | The contact section allows users to make a reservation or to send a message to the owner by filling out the form or calling the restaurant using a direct dial|

### Features Left to Implement
| Features (not included) | Explanation|
| :------------- | :---------- |
|1. Make a reservation through an agenda | This feature allows users to instantly make a reservation. To implement this feature it requires more knowledge on JavaScript |
|2. Accept a payment for a reservation | This feature allows to make a payment for a private event up to ten people. To implement this feature it requires more knowledge on JavaScript |


## Technologies Used
To following technologies has been used to achieve this project:

Resources
- [HTML](https://www.w3.org/TR/html52/) is used as the main writing language of this project
- [CSS](https://www.w3.org/Style/CSS/Overview.en.html) is used for styling the HTML text
- [JavaScript](https://www.javascript.com/) is indirectly used by Bootstrap and Google Simple Maps and Markers

Styling
- [FontAwesome](https://fontawesome.com/) is used to improve the visual design of the website 
- [contrast-ratio.com](https://contrast-ratio.com/) is used to test the visibility of the text with the background color
- [Google fonts](https://fonts.google.com/) is used for the style the font

Framework & API
- [Bootstrap](https://getbootstrap.com/) is used for its framework, specifically for this project the navigation menu, grid system and carousel
- [Google Simple Maps](https://developers.google.com/maps/documentation/javascript/tutorial) is used to place the map in this project
- [Google Markers](https://developers.google.com/maps/documentation/javascript/markers) is used to place a location marker on the map

Images
- [Adobe Photoshop CC 2019](https://www.adobe.com/uk/products/photoshop) is used to crop the images 
- [tinyjpg.com](https://tinyjpg.com/) is used to reduce the size of the images

Wireframe
- [Balsamic](https://balsamiq.com/) is used to draw wireframes for the skeleton plane

Testing
- [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools) is used to test the responsiveness of the website and to debug any problems
- [Unicorn revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln?hl=en-GB) is used to determine any overflow on the website
- [validator.w3.org](https://validator.w3.org/) is used to validate the HTML code
- [jigsaw.w3.org/css-validator](https://jigsaw.w3.org/css-validator/validator.html.en) is used to validate the CSS code



## Testing



## Key Issues


## Deployment





## Credits


### Content
- The text for the entire website is written by myself


### Media
- The photos for this website are used from:
    - Unsplash.com
    - Pixabay.com


### Acknowlegdements
- The inspiration for this project comes from a Netflix documentary called Jiro's Sushi
- Mentor
- Slack community 
- Code Institute
- Tutors
- Stackoverflow


### Source of codes
- Navbar Bootstrap
- Carousel Bootstrap
- Google maps
    - Simple maps
    - Marker
- Gallery Project Love Running Code Institute
- Zoom image Stackoverflow
- Snap scroll type  Stackoverflow







## Disclaimer
This website is for educational purposes only. All content and images are illustrative.


