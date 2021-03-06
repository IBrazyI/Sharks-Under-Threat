# Sharks-Under-Threat (Milestone Project 1)

![SharksUnderThreat](assets/images/readmeimages/responsive.png)

[Visit My Site Here](https://ibrazyi.github.io/Sharks-Under-Threat/)

## Overview
This website is an information hub for people who care about sharks and other marine life. It outlines the threats to sharks and the environment that they live in, and how we can reduce the impact we have on this. It details a bright, ocean-themed colour scheme, with large pictures and short paragraphs, to keep users' attention and communicate information quickly. 


## Table of Contents

[UX](#ux)

[Features](#features)

[Technologies Used](#technologies)

[Testing](#testing)

[Deployment](#deployment)

[Credits](#credits)

<a name="UX"></a>

## UX
### User Stories
#### First Time Visitor
- A first time visitor to the site will be drawn in by the colours and the images, making them want to discover the information underneath.
- A first time visitor wants to be able to navigate the website easily and know what page they are currently on.
- A first time visitor wants to see short but interesting pieces of text to keep their attention and help them empathise with the cause of the site.
#### Returning User
- A returning visitor will want to be able to get their friends to sign up to the page easily to support their cause.
- A returning visitor wants to find the social media information quickly and be taken to the relevant site.

### Strategy
- The strategy of the site is to provide a platform to learn information about the threats to sharks and what the visitor can do to help. This creates more awareness of the issue and encourages people to do something about it.

### Scope
- Provide visitors with basic but interesting information.
- Provide a clean-looking UX for easy navigation and information absorption.
- Provide a call to action to get the visitor involved.
- Empower visitors, encouraging them to make a difference themselves.

### Structure
#### Interaction Design
- Design a responsive website, that looks good and works well at all screen sizes.
- Responsive navigation that allows users to easily navigate between pages and know what page they are on at all times.

#### Information Architecture
- Content needs to be sectioned in a way that allows for easy uptake with little distractions.
- Images need to be displayed to flow with the page and not distract from the information sections.
- Content of pages needs to flow between sections for easy page navigation with clear titles and breaks.

### Skeleton
#### Mobile Wireframes

##### Home

![Home](/assets/wireframes/mobilehome.jpg) 
##### Threats

![Threats](/assets/wireframes/mobileactions.jpg) 
##### Actions

![Actions](/assets/wireframes/mobilethreats.jpg) 
##### Signup

![Signup](/assets/wireframes/mobilesignup.jpg)

#### Desktop/Tablet Wireframes

##### Home

![Home](assets/wireframes/pchome.jpg) 
##### Threats

![Threats](assets/wireframes/pcthreats.jpg)
##### Actions

![Actions](assets/wireframes/pcactions.jpg)
##### Signup

![Signup](assets/wireframes/pcsignup.jpg)

#### Information Design
- Information is split into small sections, each with its own heading and image to sum up the information before reading.
- More factual information is represent in smaller information boxes with separate headings and different styling to main text.

#### Interface Design
- Information is layed-out in a top-to-bottom manner, allowing for easy navigation of the page.
- Information with images are located within the same sections, making it obvious that the images relate to the information.

#### Navigation Design
- Navigation is located at the top of the page, showing importance and ease of access for the user.
- Current page is highlighted so it is obvious what page the user is currently on, so they don't get lost.

### Surface
#### Typography
Two fonts were selected for use on this site: Roboto and Oxygen. Both are from [GoogleFonts](https://fonts.google.com/).
- Roboto: this was used for the headings and titles of the page as it is a bolder and sharper font.
- Oxygen: this was used for the content of the page, slightly less bold and with more flow than Roboto. 

#### Colour Scheme

![Colour Pallet](assets/images/readmeimages/colourpallet.png)
The aim of the colour scheme was to represent the ocean, tying together the theme and the information. With this in mind,the colours are all variants of blue that gradually darken as you get deeper into the page. The brighter blue of the header represents the sky.

## Features
The site is split up into four different pages, each is designed to be responsive at all screen sizes and complete with working external links. 
1. Home - Containing a Boostrap 5 Carousel, an introduction to the site and three small information cards about seperate sharks.
2. Threats - Containing multiple sections including images and text displayed in an alternating manner.
3. Actions - Containing multiple sections including images and text displayed in an alternating manner.
4. Sign up - Containing a large background image, complete with a sign up section with forms containing; Name, E-mail, radio selector and submit button. 

#### Existing Features 
- All pages contain a Boostrap 5 nav bar, complete with links to all other pages and displays active page.
- All pages contain footer, using font awesome social media icons each with hover change of colour effect.
- Boostrap 5 Carousel, consisting of 3 images on a cycle with information labels about each picture.

#### Features Left to Implement
- Possibility of adding another page containing a gallery of multiple images of sharks, this would be responsive and contain mouseover elements.


<a name="technologies"></a>

## Technologies Used

### Languages
- HTML5 - Used as the structure of the website and container for content.
- CSS3 - Used to style and manipulate content with effects.
### Libraries
- [Boostrap](https://getbootstrap.com/) - Used for responsive design and templates for nav bar, carousel and page layout.
- [GoogleFonts](https://fonts.google.com/) - Used as the library for both fonts used in the webpage.
- [FontAwesome](https://fontawesome.com/) - Used for social media icons in footer.
- [Jquery](https://getbootstrap.com/docs/4.2/getting-started/introduction/) - Used to allow functionality of Boostrap carousel.
### Programs
- VS Code - Where all coding took place, also using integrated terminal.
- Git Hub Desktop - Used to create repository and link to online Git Hub profile.
- Git Hub - Used to host and display website.
- Adobe XD - Used for the creation of wireframes.
- [Unsplash](https://unsplash.com/) - Used to obtain most images, ready to download in specified sizes.
- [IAmResponsive](http://ami.responsivedesign.is/) - Used to test responsiveness of website, also for image displaying responsiveness at top of README.
- [Coolors](https://coolors.co/) - Used to display website colour pallet.
- [HTMLValidator](https://validator.w3.org/) - Used to check HTML code for errors.
- [CSSValidator](https://jigsaw.w3.org/css-validator/) - Used to check CSS code for errors.

<a name="Testing"></a>

## Testing

### Nav Bar
- When loading home page "home" selector on nav bar is active.
- When hovering over each nav element text changes colour as planned.
- Upon clicking on "threats" selector page is loaded and nav item is highlighted displaying that is the page you are on.
- Upon clicking on "actions" selector page is loaded and nav item is highlighted displaying that is the page you are on.
- Upon clicking on "signup" selector page is loaded and nav item is highlighted displaying that is the page you are on.
### Footer
- When hovering over social media icons they change colour as intended.
- Clicking each link opens the social media site in a new tab.
- Clicking the link to my GitHub pages takes user to the page in a new tab.
- Footer remains at the bottom of page regardless of screen size.
- Personal message and GitHub link disappear at smaller screen sizes as intended.
### Carousel
- Automatically begins rotating through images.
- Labels work and are in the correct position.
- Slide navigation buttons work with their corresponding side.
### Sign-Up
- Form placeholder text works as intended.
- Validation works on both "name" and "email" sections.
### Code Validators
- HTML Validator - No errors to show.
- CSS Validator - No errors to show.
### Devices
- Iphone 6/7/8 - Displays as intended.
- Samsung Galaxy S9 - Displays as intended.
- Samsung Galaxy S20 FE - Displays as intended.
- Ipad - Displays as intended.
- Laptop - Displays as intended.
- Desktop - Displays as intended.
### Browsers 
- Chrome - No errors.
- Firefox - No errors.
- Internet Explorer - Images slow to load.
- Microsoft Edge - No errors.
- Opera - No errors.
- Safari - No errors.
### User Stories
#### First Time Visitor
- The home page has sharp bright colours and large images drawing the eye.
- The pages have a linear flow and makes obvious what page you are currently on.
- The information on all pages is short and concise making sure they don't lose attention and only important information is passed on.
#### Returning User
- Sign up page is easy to find and minimalistic so the user knows what the purpose is.
- Social media links are easy to locate and to see for quick access.

<a name="Deployment"></a>

## Deployment

### Creating Repository
1. Created new file inside documents folder named "Coding Course" and within that created a file called "Sharks-Under-Threat(Milestone Project 1)"
2. Opened GibHub Desktop and selected "New Repository"
3. Gave the project name "Sharks-Under-Threat" and clicked "Create Repository"
4. Opened the repository in VS Code
5. Created index.html and README.md pages
6. Opened up local terminal and "Git Added" both pages.
7. Committed both pages using "Git Commit".
8. Pushed changed with "Git Push" adding my work to my Git Hub page.
9. Opened my GitHib page to see the changes.

### Viewing Site
1. After logging in to GibHub I went to the "settings" tab.
2. Upon scrolling down to "Danger Zone" I set the repository to "Public".
3. Scrolling back up to "GitHub Pages" set the source "Branch-main", "File-Root" and selected save.
4. After reloading and scrolling back down to "GitHub Pages" selected the link where my site had been published.

<a name="credits"></a>

## Credits

### Technical
- Social Media Icons- Matt Rudge Code Institute resume project.
- Boostrap 5 - Carousel, Nav Bar, List Section and structure for page layout.
- Google Fonts - All fonts
- Font Awesome - Social Media Icons

 ### Content 
 - [SharksTrust](https://www.sharktrust.org/) - Website inspiration.
 - [BiteBack](https://www.bite-back.com/?v=79cba1185463) - Website inspiration.
 - [Wikipedia](https://en.wikipedia.org/wiki/Main_Page) - Info used for Shark Information sections.

 ### Media 
Images from
- [Unsplash](https://unsplash.com/)
- [NationalGeographic](https://www.nationalgeographic.com/)

 ### Acknowledgements
- Code Institute - Running the course and providing this opportunity. 
- Maranatha Ilesanmi (Mentor) - Feedback and support during the project. 
- Slack Community - Peer reviewing my work. 



