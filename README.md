# Honda Bikers Club

![Honda Bikers Club Mockup Images](assets/media/responsive.png)

[View the live project here](https://chrisf64.github.io/Honda-Riders-Club/index.html)

## Table of contents
1. [Introduction](#Introduction)
2. [UX](#UX)
    1. [Ideal User Demographic](#Ideal-Users)
    2. [User Stories](#User-Stories)
    3. [Development Planes](#Development-Planes)
    4. [Design](#Design)
3. [Features](#Features)
    1. [Design Features](#Design-Features) 
    2. [Existing Features](#Existing-Features)
    3. [Features to Implement in the future](#Features-to-Implement-in-the-future)
4. [Issues and Bugs](#Issues-and-Bugs)
5. [Technologies Used](#Technologies-Used)
     1. [Main Languages Used](#Main-Languages-Used)
     3. [Frameworks, Libraries & Programs Used](#Frameworks,-Libraries-&-Programs-Used)
6. [Testing](#Testing)
     1. [Validator testing](#validator-testing)
7. [Deployment](#Deployment)
     1. [Deploying on GitHub Pages](#Deploying-on-GitHub-Pages)
8. [Credits](#Credits)
     1. [Content](#Content)
     2. [Media](#Media)
     3. [Code](#Code)
9. [Acknowledgements](#Acknowledgements)
***

## Introduction

This website was made to provide information regarding a fictional motorcycle club based out of Dublin, Ireland. The target audience is the bike community of Ireland. 

This website was made for the first of five Milestone projects required to complete the Diploma in Software development program at The Code Institute. 

The main requirements of this project are to build a responsive and static front-end site to present useful information to users using all the technologies learned so far, namely HTML5 and CSS3. The site is to contain no less than three pages.

## UX
### Ideal Users
The ideal user for this website is:
* Current user
* New user
* Experienced rider
* New rider

### User-Stories
#### Current User Goals
1. As a current user, I want to see regular updates to the events page.
2. As a current user, I want to easily navigate through the site and access the information I require with ease.
3. As a current user, I want to easily navigate to content I have previously viewed within a small number of steps.

#### New User Goals
1. As a new user, I want to easily navigate the entire site intuitively. 
2. As a new user, I want the information I seek to be easily accessible and relevant.

### Development-Planes
To create a website that answers the above user stories and identifies the functionality of the site. This includes an introduction, an events page, current member photos and a join us page.

#### Strategy
Strategy incorporates user needs as well as product objectives. This website will focus on the following target audience, divided into three main categories:
- **Roles:**
    - Current users
    - New users
    - Experienced riders
    - New riders

- **Demographic:**
    - All ages
    - Irish Honda riders or Honda riders residing in Ireland
    - Beginner to experienced Honda riders

The website needs to enable the **user** to:
- Retrieve the desired information:
    - How to join the club
    - Upcoming events
    - Photos from past events and of current members bikes 
    
The website needs to enable the **site manager** to:
- Update events page as necessary
- Update gallery page with new photos as they become available
- Receive new member applications from the join us page

#### Scope
Using the information from the strategy plane, the identified required features have been broken into the following two categories.
- Content Requirements:
    - The user will be looking for:
        - Information on upcoming events
        - New photos from current members and events
        - New users will require the ability to join the club
- Functionality Requirements:
    - The user will be able to:
        - Easily navigate the site to find the information they require
        - Apply to join the club and receive weekly/monthly newsletters

#### Structure
The information above was then organized in a hierarchical tree structure, a site map, showing how users can navigate through the site with ease and efficiency, with the following results:


![Site Map](assets/media/site-map.png)


#### Skeleton
Wireframes were made to showcase the appearance of the site pages while keeping a positive user experience in mind. The wireframes were created using a desktop version of [Balsamiq](https://balsamiq.com/).

## Features
### Design Features
Each page within the site has a consistent and responsive navigation system. The details of features on the site are detailed below.
- The **Header** is across the top of the page. It is not static as this would cover too much of the screen. A back-to-top button was implemented instead so users can access the navigation bar quickly.
- The **Navigation Bar** is positioned directly below the header. The navigation bar is only used for screen sizes larger than 1200px. It is then replaced by a hamburger menu.
- The **Navigation Bar** collapses into a **Hamburger Menu** that, when clicked or tapped, opens a sidebar which shows the navigation options.
- The **Footer** is 100% in width and 40px in height. It stays at the bottom of the screen at all times, on all screen sizes. Each social media link opens in a new tab. Additionally, each social media link opens a zombie related link on each respective website; eg. the Faceb

<dl>
    <dt><a href="index.html" target="_blank" alt="Survival Guild Home Page">Home Page</a></dt>
    <dd>
        The <em>Home Page</em> is a scrollable page with the main content divided into two columns on larger screens, shifting into a single column on smaller screens.
        <ul>
            <li>
                <em>Introduction</em> - This text-only section introduces the user to the page. 
            </li>
            <li>
                <em>Competition Banner</em> - Covering 100% of the width of the screen, the competition banner is not static and moves with the page. Clicking on the image will bring you directly to the Competition Page.
            </li>
            <li>
                <em>Content</em> - The World News section is a text-only column to the left of the screen on larger screen sizes. Below this is the Twitter Feed, a heading and image only column, which is another column kept to the right of the screen on larger screen sizes. The News Feed section, a text and image column, keeps to the right on larger screen sizes. On smaller screen sizes, each section expands and becomes a single long column. The order from top to bottom is World News, News Feed, and finally the Twitter Feed section. 
            </li>
            <li>
                <em>Back-to-top Button</em> - A Back-to-top button is on the bottom right of the screen, above the footer. This button will bring the user back to the top of the page from any point on the page. 
            </li>
        </ul>
    </dd>
</dl>
<dl>
    <dt><a href="survival-tips.html" target="_blank" alt="Survival Guild - Survival Tips Page">Survival Tips Page</a></dt>
    <dd>
        The <em>Survival Tips Page</em> is a scrollable page with the main content laid out in a single column, regardless of screen size.
        <ul>
            <li>
                <em>Introduction</em> - This text-only section introduces the user to the page. 
            </li>
            <li>
                <em>Page Section Buttons</em> - There are three buttons that will bring the user to each of the sections on the page. This allows the user to get to the information they require quicker with less scrolling.
            </li>
            <li>
                <em>Competition Banner</em> - Covering 100% of the width of the screen, the competition banner is not static and moves with the page. Clicking on the image will bring you directly to the Competition Page.
            </li>
            <li>
                <em>Content</em> - The content is made up of <em>text</em>, <em>images</em> and some <em>videos</em> embedded from YouTube. The images and videos change size following the screen size to provide a better user experience.
            </li>
            <li>
                <em>Back-to-top Button</em> - A Back-to-top button is on the bottom right of the screen, above the footer. This button will bring the user back to the top of the page from any point on the page. 
            </li>
        </ul>
    </dd>
</dl>
<dl>
    <dt><a href="camp-setup.html" target="_blank" alt="Survival Guild - Camp Setup Page">Camp Setup Page</a></dt>
    <dd>
        The <em>Camp Setup Page</em> has all the same features as the Survival Tips Page, only with fewer videos embedded.
    </dd>
</dl>
<dl>    
    <dt><a href="infected.html" target="_blank" alt="Survival Guild - The Infected Page">The Infected Page</a></dt>
    <dd>
        <em>The Infected Page</em> has all the same features as the Survival Tips Page, but without videos embedded and with only two Page Section Buttons.
    </dd>
</dl>
<dl>
    <dt><a href="contact.html" target="_blank" alt="Survival Guild - Contact Page">Contact Page</a></dt>
    <dd>
        The <em>Contact Page</em> is a scrollable page with two columns of content, which become a single column on smaller screen sizes.
        <ul>
            <li>
                <em>Introduction</em> - This text-only section introduces the user to the page. 
            </li>
            <li>
                <em>Content</em> - The content is made up of <em>text</em>, <em>text input boxes</em> and a <em>map</em> embedded from Google Maps. The telephone number and email have <a> elements that divert the user to their email or phone app, allowing ease of access if they wish to contact the site manager. The map changes size following the screen size to provide a better user experience.
            </li>
            <li>
                <em>Form</em> - The form contains three input boxes for names and email and a text box for the user to enter a message. There is a submit button below these which changes colour when hovered over. Sending a message through this form brings the user to a Thank You Page. 
            </li>
        </ul>
    </dd>
</dl>
<dl>    
    <dt><a href="competition.html" target="_blank" alt="Survival Guild - Competition Page">Competition Page</a></dt>
    <dd>
        The <em>Competition Page</em> is a scrollable page with two columns of content, which become a single column on smaller screen sizes.
        <ul>
            <li>
                <em>Introduction</em> - This section has text and one wide image, the same as the competition banner without the link, which introduces the user to the page. 
            </li>
            <li>
                <em>Content</em> - The content is made up of <em>text</em>, <em>text input boxes</em> and a <em>scrollable box</em>, which contains the terms and conditions of the competition, laid out into two columns on larger screens. On smaller screen sizes, the two columns rearrange to make one long column.
            </li>
            <li>
                <em>Form</em> - The form contains four input boxes for names, date of birth and email, and a question and answer using radio buttons to select the correct answer for the competition entry. There is a submit button below these which changes colour when hovered over. Submitting an entry through this form brings the user to a Thank You Page. 
            </li>
        </ul>
    </dd>
</dl>
<dl>        
    <dt><a href="dump-contact.html" target="_blank" alt="Survival Guild - Contact Thank You Page">Contact Thank You Page</a></dt>
    <dd>
        The <em>Contact Thank You Page</em> is a single page made to thank the user for contacting the Survival Guild.
        <ul>
            <li>
                <em>Content</em> - The content is made up of <em>text</em> and an <em>image</em>, which thanks the user for submitting a message on the Contact Page.
            </li>
        </ul>
    </dd>
</dl>
<dl>        
    <dt><a href="dump-competition.html" target="_blank" alt="Survival Guild - Competition Thank You Page">Competition Thank You Page</a></dt>
    <dd>
        The <em>Competition Thank You Page</em> is a single page made to thank the user for entering the Survival Guild competition.
        <ul>
            <li>
                <em>Content</em> - The content is made up of <em>text</em> and an <em>image</em>, which thanks the user for entering the competition on the Competition Page.
            </li>
        </ul>
    </dd>
</dl>
<dl>        
    <dt><a href="404.html" target="_blank" alt="Survival Guild - 404 - Page Not Found">404 - Page Not Found</a></dt>
    <dd>
        The <em>404 Page</em> is a single page that appears when a user enters the wrong address into the address bar. It is made into a mini-game/story style to entertain the user before returning to the main site. Each page in the story has a different background image that relates to the text.
        <ul>
            <li>
                <em>Content</em> - The content is made up of <em>text</em> and <em>links</em>, which allows the user to go directly to the home page or interact with the story.
            </li>
        </ul>
    </dd>
</dl>
<dl>
    <dt><a href="500.html" target="_blank" alt="Survival Guild - 500 - Internal Server Error">500 - Internal Server Error</a></dt>
    <dd>
        The <em>500 Page</em> is the same as the 404 page except for a different heading letting the user know there was an internal server error.
    </dd>
</dl>
<dl>    
    <dt><a href="bike.html" target="_blank" alt="Survival Guild - Page 2 of the Story">Page 2 of the Story</a></dt>
    <dd>
        The <em>Second Page</em> in the story is a single page that appears when a user clicks the link to continue the story. Each page in the story has a different background image that relates to the text.
        <ul>
            <li>
                <em>Content</em> - The content is made up of <em>text</em> and <em>links</em>, which allows the user to go directly to the home page or continue interacting with the story.
            </li>
        </ul>
    </dd>
</dl>
<dl>    
    <dt><a href="house.html" target="_blank" alt="Survival Guild - Page 3 of the Story">Page 3 of the Story</a></dt>
    <dd>
        The <em>Third Page</em> in the story is a single page that appears when a user clicks the link to continue the story. Each page in the story has a different background image that relates to the text.
        <ul>
            <li>
                <em>Content</em> - The content is made up of <em>text</em> and a single <em>link</em>, which allows the user to go directly to the home page.
            </li>
        </ul>
    </dd>
</dl>

### Existing Features
- **Header** - Appearing on almost every page for brand recognition.
- **Navigation Bar** - Appearing on almost every page for a consistently easy and intuitive navigable system on larger screens.
- **Hamburger Menu** - Appearing on almost every page for a consistently easy and intuitive navigable system on smaller screens.
- **Social Media Icons** - Appearing on almost every page, the icons are appropriate representations of the Social Media platforms, linking users to various zombie related pages and the developers GitHub account. The icons appear in the centre of the footer.
- **Youtube Embed** - Videos relating to the content on the Survival Tips Page and the Camp Setup Page have been embedded. These videos were embedded to emphasise the content and provide additional information relating to the content.
- **Google Maps Embed** - iframe embedding of Google maps, showing the location of Northern Ireland's Secret Bunker was added to the Contact Page. The map is resized depending on the screen size to ensure the readability of the page on mobile devices.
- **Contact Form** - A contact form is used in the Contact Page, to provide a point of contact for the user.
- **404 page** - A 404 page providing a unique user experience in the form of a mini-game/story redirects the user to the home page or, if the user chooses, to additional story pages to continue the experience.
- **500 page** - A 500 page providing a unique user experience in the form of a mini-game/story redirects the user to the home page or, if the user chooses, to additional story pages to continue the experience.
- **[Survival Tips Page](survival-tips.html "Survival Guild - Survival Tips Page")** - Providing survival tips for the users to get an understanding of how to survive the apocalypse.
- **[Camp Setup Page](camp-setup.html "Survival Guild - Camp Setup Page")** - Providing camp setup tips for the users to get an understanding of setting up a strong and safe camp during the apocalypse.
- **[The Infected Page](infected.html "Survival Guild - The Infected Page")** - Providing information relating to the Infected and how to defend yourself against them.
- **[Contact Page](contact.html "Survival Guild - Contact Page")** - Providing contact details for the Survival Guild, a map to Northern Ireland's Secret Bunker, and a form allowing the user to enter the Survival Guild.
- **[Competition Page](competition.html "Survival Guild - Competition Page")** - Providing details for the Survival Guild's competition, a terms and conditions box, and a form allowing the user to enter the Survival Guild's competition.

### Features to Implement in the future
- **Helpful Links Page**
     - **Feature** - create a page with links to external sites where users can purchase the items discussed on the various pages.
     - **Reason for not featuring in this release** - Not enough time to create this page before the submission date.

[Back to top](#Survival-Guild)

## Issues and Bugs 
The developer ran into several issues during the development of the website, with the noteworthy ones listed below, along with solutions or ideas to implement in the future.

**Background Bug** - A bug was detected early in development in the background of the main pages. While entering content onto the home page, the background colours were not covering the entire page, cutting off short and leaving a white background behind some of the content. The developer put a query to the #css-essentials channel in Slack and was provided with a simple piece of code from another user of Slack (Anthony O'Brien) which resolved the issue. It was from here that the developer was able to copy the code given as a solution to the bug, with celebratory success. This same issue occurred later on other pages, which the same piece of code was able to rectify.

<details>
<summary>Background Bug</summary>
    
![Background Bug](assets/readme-files/background-bug.png)
    
</details>

**Navigation Bar/Hamburger Menu Responsiveness Bug** - A bug was detected while introducing responsiveness to the navigation bar and hamburger menu. At 1200px exactly, both the navigation bar and hamburger menus vanished. It was found that this was caused by setting the hamburger menu to be hidden at 1200px and up, and the navigation bar to be hidden at 1200px and down. The issue was rectified simply by changing the hamburger menu to be hidden from 1201px and up instead.

**Google Maps Embedding Bug** - A bug was detected when embedding the Google map to be used for the Contact Page. The developer was previously using the web address to embed the map into the contact page. This caused an error that prevented the map from loading. The developer found that the link was to be embedded using the pre-existing embedding code provided by Google Maps, which was previously unknown to the developer. Upon implementing the correct embedding code, the map worked perfectly.

**Back-to-top Button Bug** - A bug was detected in the Back-to-top Button where the Awesome Fonts arrow up icon disappeared. It was found that the developer was using the wrong class to colour the icon, causing it to appear invisible. This was rectified by introducing a new class name of "top-home", to which the colouring was applied. In addition to this, during the validation of the code, an error appeared in the code for the button. It appears that the code borrowed from <a href="https://secluded.site/adding-a-better-scroll-to-top-button-without-javascript/">Secluded.Site</a> was causing the problem. While the code worked perfectly, the creator placed a <button> element as a descendant of the <a> element, causing the error.

**Double-click Ads Link Bug** - A bug was detected in the developer tools console. On the survival-tips.html and camp-setup.html pages, a bug appeared saying "Loading failed for the <script> with source 'http://static.doubleclick.net/instream/as-status.js'". After careful testing, the source of the bug was found to be the YouTube videos embedded in the page, which the developer was unable to alter to remove the bug. 

<details>
<summary>Background Bug</summary>
    
![Ad double-click Bug](assets/readme-files/double-click-bug.PNG)

## Technologies Used
### Main Languages Used
- [HTML5](https://en.wikipedia.org/wiki/HTML5 "Link to HTML Wiki")
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets "Link to CSS Wiki")

### Frameworks, Libraries & Programs Used
- [Google Fonts](https://fonts.google.com/ "Link to Google Fonts")
    - Google fonts was used to import the fonts "Special Elite", "Open Sans", "Oswald" and "Nosifer" into the style.css file. These fonts were used throughout the project.
- [Font Awesome](https://fontawesome.com/ "Link to FontAwesome")
     - Font Awesome was used on almost all pages throughout the website to import icons (e.g. social media icons) for UX purposes.
- [GitPod](https://gitpod.io/ "Link to GitPod homepage")
     - GitPod was used for writing code, commiting, and then pushing to GitHub.
- [GitHub](https://github.com/ "Link to GitHub")
     - GitHub was used to store the project after pushing
- [Balsamiq](https://balsamiq.com/ "Link to Balsamiq homepage")
     - Balsamiq was used to create the wireframes during the design phase of the project.
- [Figma](https://www.figma.com/ "Link to Figma homepage")
     - Figma was used to create the concept art during the design phase of the project.
- [Am I Responsive?](http://ami.responsivedesign.is/# "Link to Am I Responsive Homepage")
     - Am I Responsive was used in order to see responsive design throughout the process and to generate mockup imagery to be used.

[Back to top](#Survival-Guild)
    
## Testing

## Testing 

The site was tested for usability and navigation in Chrome, Firefox, Brave and Safari. The site was tested for responsiveness in all four browsers but more specifically in Chrome, using Developer Tools where it resulted in each page behaving as it should when screen sizes were changed.
The site was then run through Lighthouse with particular focus on Accessibility where it scored 100%.

![Lighthouse result](media/lighthouse.png)

Apart from 'schoolboy' errors, no bugs were found during testing.

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)

- CSS
  - One error was initially found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)
  The error was triggered by a stray curly bracket and was tidied up.


## Deployment

This project was developed using [GitPod](https://www.gitpod.io/ "Link to GitPod site"), which was then committed and pushed to GitHub using the GitPod terminal.

### Deploying on GitHub Pages
To deploy this page to GitHub Pages from its GitHub repository, the following steps were taken:

1. Log into [GitHub](https://github.com/login "Link to GitHub login page") or [create an account](https://github.com/join "Link to GitHub create account page").
2. Locate the [GitHub Repository](https://github.com/Irishbecky91/survival-guild "Link to GitHub Repo").
3. At the top of the repository, select Settings from the menu items.
4. Scroll down the Settings page to the "Pages" section.
5. Under "Source" click the drop-down menu labelled "None" and select "Main".
6. Upon selection, the page will automatically refresh meaning that the website is now deployed.
7. Scroll back down to the "Pages" section to retrieve the deployed link.
    

    
## Credits 

### Content
- Some of the text used in the the various pages were borrowed and adapted from various sites, listed below.
    - [Reserve America](https://www.reserveamerica.com/outdoors/how-to-start-a-campfire.html "Link to Reserve America - How to Start a Campfire")
    - [Seeker](https://www.seeker.com/top-ways-to-purify-water-in-the-wilderness-1765491027.htmlhttps://www.seeker.com/top-ways-to-purify-water-in-the-wilderness-1765491027.html "Link to Seeker - Purifying Water")
    - [Survival Freedom]( https://survivalfreedom.com/10-ways-to-build-a-shelter-out-of-natural-resources/ "Link to Survival Freedom - Building Shelter from Natural Resources")

### Media
- Almost all images were sourced from the various artists from [Unsplash](https://unsplash.com/ "Link to Unsplash") and [Pixabay](https://pixabay.com/ "Link to Pixabay").
- The images of "The infected" were sourced from [Soufiane Idrassi](https://www.artstation.com/cgsoufiane "Link to Soufiane Idrassi's account on Art Station") through the website [Art Station](https://www.artstation.com/ "Link to Art Station Home Page").
- All videos were sourced from various channels on [YouTube](https://youtube.com/ "Link to YouTube Home Page")

### Code 
The developer consulted multiple sites in order to better understand the code they were trying to implement. For code that was copied and edited, the developer made sure to reference this with the code. The following sites were used on a more regular basis:
- [Stack Overflow](https://stackoverflow.com/ "Link to Stack Overflow page")
- [W3Schools](https://www.w3schools.com/ "Link to W3Schools page")

[Back to top](#Survival-Guild)

## Acknowledgements

- I would like to thank my family for their valued opinions and critic during the process of design and development.
- I would like to thank my tutor, Kasia, and my mentor, Seun, for their invaluable help and guidance throughout the process.
- Lastly, I would like to extend my deepest gratitude to the amazing people in Slack who helped me rigorously test every aspect of my site.

[Back to top](#Survival-Guild)

***
