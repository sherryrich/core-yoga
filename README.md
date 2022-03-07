# Core Yoga

Core Yoga is Dublin’s latest yoga studio specialising in core strength. With two new locations Dublin Docklands and Ranelagh. Dublin, Ireland’s capital, is the perfect place for this latest venture with its dynamic professional workforce with an emphasis on health. The aim of this site is to introduce users to the new locations and show the users some basic information such as availability of classes and contact information.

A deployed link to the website can be found [here](https://sherryrich.github.io/core-yoga/)

## Showcase
![Preview](https://github.com/sherryrich/core-yoga/blob/main/docs/ami_responsive_core_yoga.JPG)

## Features 

### Navigation
* The name of the yoga studio, Core Yoga is featured in the top left of the page.
* The main navigation links are located to the top right of the webpage. Classes and contact which link to the different pages. From here users can easily navigate from page to page across all devices without using "back" button.
* The navigation bar also clearly tells the users the name of the yoga studio and shows easily where to find links to the other pages of the website whilst showing the user what page they are currently on with an orange underline.

![Preview](https://github.com/sherryrich/core-yoga/blob/main/docs/core_yoga_navbar.PNG)

### Header
* The header contains a main landing image which shows a woman in a yoga position.
* To the right of this image there is a text-box which highlights the 2 locations and inviting new members to join.
* This section provides clear information on what this site is about and who it is for.

![Preview](https://github.com/sherryrich/core-yoga/blob/main/docs/core_yoga_hero_image.PNG)

### Home Page

The homepage will be a landing page for the user and give them the warm welcome feeling and inviting them to join the studio.
The landing includes a large full with photograph to show the user that this site relates to Yoga.

This section introduces the user with an eye catching animation to grab their attention.

BENEFITS OF CORE YOGA
3 sections advising the user to read the benefits of Yoga to their health.
This should entice the user to engage more with the rest of the website and consider joining one of the studios.

![Preview](https://github.com/sherryrich/core-yoga/blob/main/docs/core_yoga_benefits.PNG)

The Footer
The footer section includes links to the 4 main social media sites for Core Yoga. The links will intentionally open in a new tab to allow easy navigation for the user.
The footer is to encourage the user to keep connected with Core Yoga via social media

### Classes Page
* Classes: This page displays a class timetable with the Day, Time, Class, Location, Level and Duration of each class.

![Preview](https://github.com/sherryrich/core-yoga/blob/main/docs/core_yoga_class_timetable.PNG)

### Contact Page
* Contact Page: This is the contact page for users to be able to enquire further about joining Core Yoga.
* The form collects name, email and the studio location which the user is interested  contacting.
* The user will also be required to submit their full name and email address.

![Preview](https://github.com/sherryrich/core-yoga/blob/main/docs/core_yoga_contact_form.PNG)

### Footer
* The footer is shown on the bottom of all 3 pages and provides the user with links to the various social media accounts to Facebook, Twitter, YouTube and Instagram.
* When the user scrolls over the social media icons they change color to orange to highlight the icon.

![Preview](https://github.com/sherryrich/core-yoga/blob/main/docs/core_yoga_social_media_links.PNG)

### Features Left to Implement
* An iframe showing the locations of the 3 Studios on Google maps.

## Color Palette

![Preview](https://github.com/sherryrich/core-yoga/blob/main/docs/core_yoga_color_palette.PNG)

## Skeleton
Wireframes Desktop
![Preview](https://github.com/sherryrich/core-yoga/blob/main/docs/wireframe_homepage.PNG)


## Lighthouse Report
![Preview](https://github.com/sherryrich/core-yoga/blob/main/docs/core_yoga_lighthouse.PNG)

## Technologies Used

I intentionally did not use Bootstrap on this project as I wanted to learn and master HTML & CSS without reliance on this CSS framework.

* HTML5
* CSS3
* Google Chrome Dev tools for debugging
* Google Light house for audits

## Testing

* Rigorous testing was completed via Google Chrome Dev tools. Responsive design from a mobile first strategy. Most notably iPhone SE (375 x 667) and larger screen sizes.
* I tested in various browsers, Chrome, Firefox, Safari and Edge.
* I had tested Internet ExpoExplorer however this is no longer supported so was omitted from further testing.
* I confirmed that the navigation in the header links to the various pages classes, contact & home all worked on each page so navigation was seamless.
* I confirmed the form works in every input field and required fields worked as expected and the form submitted successfully in each browser.

### Validator Testing

* The W3C Markup Validator and W3C CSS Validation Service were used to validate each page to sure no errors were shown upon submission.

The W3C Markup Validator [results]
W3C CSS Validation Service [results]

### Bugs
* Positioning of hero image on y-axis to show centrally.
* Initially I used collspan to specify the alignment of the content in the table however from reading on online I noticed that this attribute has been deprecated.
* Initially when I deployed my project to Github I noticed that the images didn't display. This was due to absolute URL file path being incorrect. Removing the / resolved this bug.
* I couldn’t resolve CSS issues with Internet Explorer  however after querying this I was informed by my mentor that Internet Explorer is no longer supported.
* Z-index was used to ensure benefits header is in front.
* During testing the W3C Validator flagged the duplication of ID usage.
* Lighthouse advised of Semantic improvements to be made such as H3 heading coming before a H2.

### Unfix Bugs
No unfixed bugs

## Deployment
* The current deployment of this project was done using Gitpod.
* I used the gitpod interface to write the code and as it is linked with Github as it was easy to use the terminal to commit my files and push to my repository.
* The deployed website is hosted on Github pages for easy viewing without having to clone or fork the repository to view the running website. Deployment was done by clicking on the settings tab on my repository then navigating to "Github pages" Changing the source from none to master
* I deployed the site to GitHub pages. 
* A deployed link to the website can be found [here](https://sherryrich.github.io/core-yoga/)
* In the GitHub repository go to the Settings tab.
* Next from the source section drop-down select Master Branch
* once master branch is slected the page provides the link to the completed website. This can take a minute to activate and show live.

###  If you wish to run this project locally.
- Click clone / download
- Choose your preffered method (Zip or github desktop)
- Open in your preffered IDE
- Run on local server

### Credits
* [Code Institute](https://codeinstitute.net/ie/) Full Stack Developer Course
* [W3Schools](https://www.w3schools.com/) - constant source of help and inspiration
* [MDN](https://developer.mozilla.org/en-US/) - wealth of information
* Udemy [The Web Developer Bootcamp 2002](https://www.udemy.com/course/the-web-developer-bootcamp/)
* Form Examples [HTML&CSS Book](https://www.htmlandcssbook.com/code-samples/chapter-06/)
* The code to make the hero-image and animation effect on the homepage was taken from the CI [Love Running](https://github.com/Code-Institute-Org/love-running-2.0) project.
* Inspiration for this README was taken from [Love Running](https://github.com/Code-Institute-Solutions/readme-template)
* Am I Responsive?[Am I Responsive?](http://ami.responsivedesign.is/)A tool for taking a quick snapshot of the responsive breakpoints of the website to visualise how the site will look on different device screen sizes in one place. The resulting screenshot is also used as the README.md logo image.

### Media
* The images for this project were sourced from [Pexels](https://www.pexels.com/)

### Content
* The icons in the footer were taken from Font [Awesome](https://fontawesome.com/)
* [Google fonts](https://fonts.google.com/) for the fonts Roboto, Montserrat, Sans-Serif

This project is for educational use only and was created for the Code Institute Module

### Acknowledgements
* To create this website, I relied  on the material covered in the Full Stack Development course by Code Institute. I also relied on information from Code InstituteM Slack Community Channels, Udemy, W3Schools & MDN for Online Web Tutorials and resources.
* Gerard McBride my tutor.

Created by Richard Sherry :smiley: