# Saitama Dainingu | A Private Dining Experience
Code Institute Milestone Project 1 - Static Front End Website

This project is a website that contains three pages: a Landing, About and Gallery page. The purpose of this website is to attract and inform new customers by a simple, but strong, visual design. The website contains functional information, such as a contact form and a downloadable menu, as well as an image gallery and a background story to balance the purpose of the website.

![alt text][logo]

[logo]: https://raw.githubusercontent.com/MatthewYong/milestone-project-1/master/readme/images/image-landingpage-device.png

## UX
To understand what kind of website we need to deliver to the client, we need to define the development process of each stage. This can be done by analyzing and breaking down the development process of the project into five planes:

### 1. Strategy Plane
The strategy plane defines the business objective and the user needs (goals). The goals for this project are defined as:

| Business Goal | Customer Goals |
| :------------- | :---------- |
|  As an owner of the restaurant I want the website to: | As a customer I want to:  |       
| 1. Be eye-catching and attract customers by using a simple and unique design  | 1. Contact the restaurant for a reservation or more information | 
| 2. Have the ability to contact the owner or make a reservation through a form | 2. To be more familiar with the chef’s cooking and history of this restaurant 
| 3. Increase marketing by having social media links on the website | 3. See photos of the chef's dishes | 
| 4. Send newsletters for latest update | 4. See the price of the menu and download a PDF version of the menu  | 
| 5. To have the ability to accept a payment for a reservation  | 5. Make a reservation through an agenda | 


### 2. Scope Plane
The scope plane defines the features that are and are not possible to include in the website. This will be further in detail explained in the next chapter. A summary of the included and not included features are:

| Features (included) | Future features (not included)|
| :------------- | :---------- |
|1. Navigation menu bar: Home, About, Gallery, Contact | 1. Make a reservation through an agenda|
|2. Hero images | 2. Accept a payment for a reservation|
|3. Reservation information and a downloadable PDF menu| 3. Form API reference|
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
|3. Reservation information and a downloadable PDF menu| The information section let users know what to expect and allows users to open a link to menu which can be downloaded as well.|
|4. Location of the restaurant through Google maps | The location of the restaurant allows users to plan their visit using the familiarity of Google Maps|
|5. Footer with copyright and social media links| The footer allows users to receive the latest updates by subscribing to the restaurant's pages|
|6. Photo gallery | The photo gallery allows users to be more familiar with the chef's dishes|
|7. About page | The about section allows users to be more familiar with the history of the owner |
|8. Contact section | The contact section allows users to make a reservation or to send a message to the owner by filling out the form or calling the restaurant using a direct dial|

### Features Left to Implement
| Features (not included) | Explanation|
| :------------- | :---------- |
|1. Make a reservation through an agenda | This feature allows users to instantly make a reservation. To implement this feature it requires more knowledge on JavaScript|
|2. Accept a payment for a reservation | This feature allows to make a payment for a private event up to ten people. To implement this feature it requires more knowledge on JavaScript|
|3. Form API reference | This feature allows the owner to receive the message send by customers through the contact form|


## Technologies Used
To following technologies has been used to achieve this project:

Resources
- [HTML](https://www.w3.org/TR/html52/) is used as the main writing language of this project
- [CSS](https://www.w3.org/Style/CSS/Overview.en.html) is used for styling the HTML text
- [JavaScript](https://www.javascript.com/) is indirectly used by Bootstrap and Google Simple Maps and Google Markers

Styling
- [FontAwesome](https://fontawesome.com/) is used to improve the visual design of the website 
- [Contrast-ratio.com](https://contrast-ratio.com/) is used to test the visibility of the text with the background color
- [Google fonts](https://fonts.google.com/) is used for the style the font

Framework & API
- [Bootstrap](https://getbootstrap.com/) is used for its framework. Specifically, for this project: the navigation menu, the grid system and the carousel
- [Google Simple Maps](https://developers.google.com/maps/documentation/javascript/tutorial) is used to place the map in this project
- [Google Markers](https://developers.google.com/maps/documentation/javascript/markers) is used to place a location marker on the map

Images
- [Adobe Photoshop CC 2019](https://www.adobe.com/uk/products/photoshop) is used to crop the images 
- [Tinyjpg.com](https://tinyjpg.com/) is used to reduce the size of the images

Wireframe
- [Balsamic](https://balsamiq.com/) is used to draw wireframes for the skeleton plane

Testing
- [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools) is used to test the responsiveness of the website and to debug any problems
- [Unicorn revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln?hl=en-GB) is used to determine any overflow on the website
- [Validator.w3.org](https://validator.w3.org/) is used to validate the HTML code
- [Jigsaw.w3.org/css-validator](https://jigsaw.w3.org/css-validator/validator.html.en) is used to validate the CSS code


## Testing
The testing of the website has been carry out through [W3C Markup Validator](https://validator.w3.org/), [W3C CSS Validator](https://jigsaw.w3.org/css-validator/validator.html.en) and test scenarios. The results and issues from W3C Markup Validator and W3C CSS Validator will be discussed in the next chapter 'Key Issues'. 

### Test Scenarios
The following test scenarios have been carried out:

- Navigation menu
    1. Go to the navigation menu on the landing page
    2. Click on one of the titles on the navigation bar and verify that:
        - The logo **'Saitama Dainingu'** will redirect to the landing page
        - **'Home'** will redirect to the landing page
        - **'About'** will redirect to the about page
        - **'Gallery'** will redirect to the gallery page
        - **'Contact'** will scroll the page down to the contact section
    3. Verify that step 2 will work on the about and the gallery page

- Hero Image
    1. Go to the landing page
    2. Click on left or right arrow and verify that the next or previous image will be shown
    3. Refresh the page and wait 10 second and verify that the next image will be shown
    4. Click on the 'Make a Reservation' button and verify that the page will scroll down to the contact section

- Download PDF menu
    1. Go to the landing page
    2. Scroll down and click on the 'Menu' button and verify that a new tab will be opened
    3. Go the opened tab and verify that the menu can be downloaded as PDF

- Photo gallery
    1. Go to the gallery page
    2. Select one image at a time and verify that a new tab will be opened
    3. Go the opened tab and verify that the same selected image is shown

- Contact form
    1. Go to the landing page
    2. Click on the 'Send' button and verify that empty fields needs to be filled
    3. Fill in the form and click on the 'Send' button
    4. Verify that a new page will be opened and that the page will scroll down to the contact section
    5. Verify that step 2-4 will work on the about and the gallery page

- Location
    1. Go to the landing page
    2. Under the contact section click on the address and verify that a new page with Google Maps will open and that the same address will be shown on Google maps
    3. Verify that step 2 will work on the about and the gallery page

- Phone
    1. Go to the landing page
    2. Under the contact section click on the phone number and verify that a you can direct dial the number
    3. Verify that step 2 will work on the about and the gallery page

- Location map
    1. Go to the landing page
    2. Under the contact section view the map, hover over the marker on the map and verify that the marker will show 'Saitama Dainingu'
    3. Verify that step 2 will work on the about and the gallery page

- Social media links
    1. Go to the landing page
    2. Scroll down to the footer and click on every social media link
    3. Verify that every link open a new page and redirect the page to the regarded link
    4. Verify that step 2 and 3 will work on the about and the gallery page


### Browser and Mobile Devices
All of test scenarios have been carried out in the following browsers and mobile device:

#### Browser Testing
- Google Chrome - version 81.0.4044.122 (64-bit)
- Mozilla Firefox - version 75.0 (64-bit)
- Microsoft Edge - version 81.0.416.64 (64-bit)
- Internet Explorer - version 11.719.18362.0

#### Mobile Device Testing through Chrome DevTools
- Moto G4 
- Galaxy S5
- iPhone 5/SE/6/7/8/Plus
- iPad (Pro)


## Key Issues
### W3C Markup validator
### W3C CSS Validator




### Browser and mobile testing
- Issues were found on Internet Explorer:
    - Inputted text on contact form is not visible
    - Smooth scrolling does not function 

- No issues were found on Google Chrome, Mozilla Firefox and Microsoft Edge


- No issues were found on any mobile devices






## Deployment
### GitHub Pages
To publish the website, the following steps needs to be taken:

1. Open GitHub and go to your site's **'Repositories'**
2. Go to **'Settings'**
3. Scroll down until you see **'GitHub Pages'**
4. Under GitHub pages, click on the dropdown under **'Source'** and select the **'Master Branch'** option
5. A green box should appear with the following message **'Your site is published at.../'**

![alt text][deploy]

[deploy]:https://raw.githubusercontent.com/MatthewYong/milestone-project-1/master/readme/images/image-github-deployment.JPG

For more information on how to deploy a website on GitHub, please visit [here](https://help.github.com/en/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

### Cloning a Repository 
To make a clone of the website and work locally, the following steps needs to be taken:
1. Go to the main page of the GitHub repository and click on the dropdown menu **'Clone or download'**
2. Copy the URL and go to your local IDE (Integrated Development Environment)
3. In the terminal of your IDE type in **'git clone'** and the paste the URL copied from step 2 
4. Press **Enter** and the clone will be created

For more information on cloning repositories through a command line or cloning to a GitHub Desktop, please visit [here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

## Credits
### Content
- The text for the website is entirely written by myself. However, the inspiration for this project comes from a Netflix documentary called [Jiro Dreams of Sushi](https://en.wikipedia.org/wiki/Jiro_Dreams_of_Sushi)

### Media
- All photos for this project are used from:
    - Unsplash.com
    - Pixabay.com

### Source of codes

The following codes were inspired or taken from:
- [Bootstrap Carousel](https://getbootstrap.com/docs/4.0/components/carousel/): Used in index.html code line 25 for sliding/fading hero images
- [Bootstrap Navbar](https://getbootstrap.com/docs/4.0/components/navbar/): Used in the navigation menu on all pages from the website 
- [Bootstrap Grid](https://getbootstrap.com/docs/4.0/layout/grid/): Used in the contact section on all pages of the website
- [Google Maps and Markers](https://developers.google.com/maps/documentation/javascript/examples/map-simple): Used in the contact section on all pages of the website
- [Code Institute- Project Love Running](https://courses.codeinstitute.net/): Used in gallery.css code line 16 for creating a photo gallery

Code used in the previous versions of the website:
- [StackOverflow](https://stackoverflow.com/questions/44690752/zoom-background-image-only): Used for zooming in on background image in index.html
- [CSS-Tricks](https://css-tricks.com/practical-css-scroll-snapping/): Used for auto-scrolling one section at a time in index.html


### Acknowledgement
The completion of this project could not have been possible without support and the extensive knowledge of other people. My appreciation goes to:
- Gerard (Gerry) McBride, my mentor, for giving me guidance throughout the project and giving me useful tips to finish a good project
- Tutor Scott from Code Institute, for giving me tips on what needs to be included in this project
- Code Institute, for the valuable lessons through videos and exercises
- StackOverflow, for giving me code support 
- Slack community, for reviewing my project, giving me new ideas and code support. In particular Richard Wells for arranging a project call to give us tips and tricks for milestone project 1 and anna_ci for her tips on how to deploy the website.

## Disclaimer
This website is for educational purposes only. All content and images are illustrative.


