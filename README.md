# **Black Rose Tattoo**

![Black Rose Tattoo shown on a variety of screen sizes](assets/images/black-rose-tattoo.png)

Visit the deployed website: [Black Rose Tattoo](https://veebee4.github.io/blackrosetattoo/)

## **Project Description**

This website has been built to improve on the current, existing squarespace website for Black Rose Tattoo, I have undertaken this project as the shop belongs to a good friend of mine, also I have a passion for tattoos and this is the studio that I go to.
I wanted to create this website to improve on the aesthetics and accessibility for information about Black Rose Tattoo, its tattoo artists and booking appointments.

[YouGov](https://yougov.co.uk/society/articles/43350-should-visible-tattoos-be-allowed-workplace) wrote an article about tattoos and the workplace, which showed that a 1/4 of Britons have tattoos and this is likely to keep growing with the acceptance of tattoos becoming a more widespread global opinion in recent years.

## CONTENTS

* [User Experience](#user-experience-ux)
  * [User Stories](#user-stories)

* [Design](#design)
  * [Colour Scheme](#colour-scheme)
  * [Typography](#typography)
  * [Imagery](#imagery)
  * [Wireframes](#wireframes)
  * [Features](#features)
    * [Future Implementations](#future-implementations)
  * [Accessibility](#accessibility)

* [Technology Used](#technology-used)
  * [Languages Used](#languages-used)
  * [Frameworks, Libraries & Programs Used](#frameworks-libraries--programs-used)

* [Deployment & Local Development](#deployment--local-development)
  * [Deployment](#deployment)
  * [Local Development](#local-development)
    * [How to Fork](#how-to-fork)
    * [How to Clone](#how-to-clone)

* [Testing](#testing)
  * [Chrome DevTools Audit Report](#chrome-devtools-audit-report)
  * [Solved Bugs](#solved-bugs)
  * [Known Bugs](#known-bugs)
  
* [Credits](#credits)
  * [Code Used](#code-used)
  * [Content](#content)
  * [Acknowledgments](#acknowledgments)

--- 
![Black Rose Tattoo Banner](assets/images/brt-logo.png)

## User Experience UX

- ### User Stories

- #### First Time Visitor Goals

  1. As a first time visitor, I want to be able to navigate through the site and find the content I want without difficulty.
  2. As a first time visitor, I want to be able to book in easily.
  3. As a first time visitor, I want to have initial tattoo questions answered on a page so I don't have to contact anyone first.
  4. As a first time visitor, I would like to view current/existing work by the artist.

- #### Returning Visitor Goals

  1. As a returning visitor, I want to be able to easily and quickly find to contact details again.
  2. As a returning visitor, I want to be able to gain quick access the artists' up-to-date work.

- #### Frequent Visitor Goals

  1. As a frequent visitor, I want to be able to see if any new artists have been added to the studio.

---

### Design

- #### Colour Scheme

  I initially chose a colour scheme of grey and pink but once I had applied the colours early on I decided that it did not work and did not provide the look I was going for. I then found a colour palette of shades of teal which I have used and also added to with selections of my own, complimented with gold accents, with black and white details to provide the necessary distinction between background and content.
  All colours are displayed within a commented section of my css so that if you need to change anything, you can make the changes in this section and it will apply to the classes, some of which cover repeated elements throughout the website.

| Website Element                   | Colour           |
| --------------------------------- |:----------------:|
| Background of Navigation & Footer | #013636          |
| Background of All Pages           | #006666          |
| Page Titles                       | #011d1d          |
| Body Text & Icons                 | White            |

  I used a slightly lighter teal, for the background of all pages to distinguish the difference between header, footer and main section of the webpage.
  All text and icons are in white to ensure this is easily visible to the user.
  I have used a darker teal for the page titles, I made this a little darker than the below colours on the palette I had chosen, again to really make the text distinguishable.

![Black Rose Tattoo Colour Scheme](documentation/colour-palette.png)

- #### Typography

  Google Fonts was used to import the chosen fonts for use on the site.

  - For the Page Title I have used the google font [Pirata One](https://fonts.google.com/specimen/Pirata+One?query=pirata+one) Pirata One is a font that is close to black lettering which is a calligraphy style commonly used by tattoo artists.

  ![Pirata One Font Example](documentation/pirata-one-example.png)

  - I have also chosen [Montserrat](https://fonts.google.com/specimen/Montserrat?query=montserrat) as my other font, which is clear and easily readable.

  ![Montserrat Font Example](documentation/montserrat-example.png)

  I have also named the sans-serif font as a fallback font in case the other chosen fonts do not show for any reason.

- #### Imagery

  - This is an important aspect of this website as tattoo's are a visual commodity, images will showcase the studio and also examples of the artists work. The main image on the home page gives the user a sneak peak at the tattoo studio before setting foot in the physical location.
  - Any images used have been obtained with permission by the Studio owner.

- #### Wireframes

  - Home Page Wireframes [Desktop](documentation/wireframes/home-wireframe.png) [Mobile](documentation/wireframes/home-mobile-wireframe.png)
  - Meet The Artists Wireframe [Tablet](/documentation/wireframes/meet-the-artists-tablet-wireframe.png)
  - FAQ Page Wireframe [View](documentation/wireframes/faqs-wireframe.png)
  - Contact Us Page Wireframe [View](documentation/wireframes/contact-us-wireframe.png)
  - Booking In Page Wireframe [Desktop](documentation/wireframes/book-in-wireframe.png) [Mobile](documentation/wireframes/book-in-mobile-wireframe.png)

  My website design has been slightly changed and tweaked from the original design on the wireframes, this is purely down to aesthetics.

## Technology Used

This project is written using HTML & CSS in Gitpod. I have also used flex-box and bootstrap to make the site responsive, and it is currently being hosted on GitHub.

## Features

The website comprises of a homepage, meet the artists page to introduce the artists working at the studio, an faq page, along with a contact and booking in page. The form on the booking in page re-directs to a thank you page once the form has been filled in and the submit button has been pressed.

- Responsive on all devices, using a mobile first approach.
- Interactive Menus and links on all pages.
- Street Map.
- Small logo's on the header and footer that act as a link back to the home page.
- Main logo that appears on every page.

#### Future Implementations

For future implementations I would like to:

1. Add pages to showcase a gallery of each artists work so that the user doesn't have to visit social media to view their work.
2. Have a page which branches off into the other services that are offered at the studio; Laser removal and Semi-Permanent Makeup.
3. Create a more detailed booking in form.
4. Create a shop to sell all the artists merchandise.
5. Improve performance of whole site.

### Accessibility

I have been trying to make the project and website as accessible as possible. I have been doing this by:

* Using semantic HTML.
* Using the hover element on all buttons on the site to make it known to the user that they are hovering over a button.
* Making sure all pictures have an alt attribute.
* Ensuring that there is a enough colour contrast throughout the site and the background (and background image) does not distract from the content.
* Displaying appropriate title on page tab, so users can easily see where they are on the site, just by looking at the tab.

### Languages Used

- HTML5
- CSS3
- Javascript (Scripts copied from tutorials only to make certain elements work)

### Frameworks, Libraries & Programs Used

   *[Bootstrap 4.3.1:](https://getbootstrap.com/docs/4.4/getting-started/introduction/)
    - Bootstrap was used to create a responsive navigation menu to allow for a hamburger menu once the screen size reduced from desktop/
   *[Hover.css:](https://ianlunn.github.io/Hover/)
    - Hover.css was used on buttons and the faq questions to allow feedback for the user.
   *[Google Fonts:](https://fonts.google.com/)
    - Google fonts were used by importing the fonts Pirata One and Montserrat, into the style.css file which has been used on all pages within the project.
   *[Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used to add icons for aesthetic purposes.
   *[jQuery:](https://jquery.com/)
    - jQuery comes with Bootstrap and makes the navbar responsive.
   *[Git](https://git-scm.com/)
    - The git command was used for version control via the terminal in Gitpod, to commit to Git and Push to GitHub.
   *[GitHub:](https://github.com/)
    - GitHub is used to save and store the files and projects code after being pushed from Git.
   *[Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create wireframes.
   *[Google Developer Tools](https://developers.google.com/web/tools) 
   - To troubleshoot and test features, solve issues with responsiveness and styling.
   *[Am I Responsive?](http://ami.responsivedesign.is/)
   - To show the website home page image on a range of devices.
   *[Procreate](https://procreate.com/)
   - Used to design the text logo and the mini logo for the header and footer.


## Deployment & Local Development

### Deployment

The site is deployed using GitHub Pages - [Black Rose Tattoo](https://veebee4.github.io/blackrosetattoo/).

To Deploy the site using GitHub Pages:

1. Login (or signup) to Github.
2. Go to the repository for this project, [veebee4/blackrosetattoo](https://github.com/veebee4/blackrosetattoo).
3. Click the settings button.
4. Select pages in the left hand navigation menu.
5. From the source dropdown select main branch and press save.
6. The site has now been deployed, please note that this process may take a few minutes before the site goes live.

### Local Development

#### How to Fork

To fork the repository:

1. Log in (or sign up) to Github.
2. Go to the repository for this project, [veebee4/blackrosetattoo](https://github.com/veebee4/blackrosetattoo)
3. Click the Fork button in the top right corner.

#### How to Clone

To clone the repository:

1. Log in (or sign up) to GitHub.
2. Go to the repository for this project, [veebee4/blackrosetattoo](https://github.com/veebee4/blackrosetattoo)
3. Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
4. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
5. Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.

- - -

## Testing

- #### First Time Visitor Goals

  1. As a first time visitor, I want to be able to navigate through the site and find the content I want without difficulty.
    1. Upon loading the home page, users are automatically presented with a simple, clean and easily readable navigation bar to go to the page of their choice, each navigation link states the page unambiguously and plainly, and displays a bottom border when the user hovers over it, providing feedback to the user that they are hovered over that page. Underneath there is a logo clearly displaying 'Black Rose Tattoo', so the user knows exactly where they are.
    2. The navigation bar sticks to the top of each page when the user scrolls further down the page, so all pages are easily accessible at any point during the users' visit.
    3. On the booking in page, there is a form to provide all information for the user to be able to book in effectively. On pressing submit, the user is redirected to a thank you page and the header and footer is accessible on this page so the user can take themselves back to any other page, if they wish.

    [User Story 1](documentation/testing/user-stories/user-story-1-screenshot.png)

  2. As a first time visitor, I want to be able to book in easily.
    1. When the visitor loads the home page, within the nav bar at the top of the page there is a navigation link to the booking in page, or the user can scroll down to see an image of the studio that contains a centered booking in button, this means the user can access the booking in page from all pages, at any point within the page.
    2. The booking in form itself is easy to read and simple to use with each text area appropriately labelled, what it is for. The input areas and checkbox all have the required attribute (apart from the uploading of reference photos which is not required), so the user can also ensure they are booked in effectively as all information is required by the studio.

    [User Story 2](documentation/testing/user-stories/user-story-2-screenshot.png)

  3. As a first time visitor, I want to have initial tattoo questions answered on a page so I don't have to contact anyone first.
    1. The user can easily navigate to the clearly marked FAQ page from any page on the website. They can then view the questions via a collapsable element meaning they can just view the questions they require answers for.
    2. Each question is a button which changes to a lighter colour to show feedback to the user as to which question they are currently hovering over. The user then needs to click on the question and the answer is expanded below.

    [User Story 3 - Question Highlighted](documentation/testing/user-stories/user-story-3-screenshot.png)
    [User Story 3 - Question Clicked](documentation/testing/user-stories/user-story-3-screenshot-2.png)

  4. As a first time visitor, I would like to view current/existing work by the artist.
    1. The user can navigate to the 'Meet The Artists' page, whereby they will find links to the artists' social media and a sneak peak an example of each artists' work.
    2. The links to each artists Instagram are clearly marked underneath each artist picture and introduction. These links have been coded to open into a new tab so the user isn't taken away from the main website completely.

    [User Story 4](documentation/testing/user-stories/user-story-4-screenshot.png)

- #### Returning Visitor Goals

  1. As a returning visitor, I want to be able to easily and quickly find to contact details again.
    1. The user can go straight to the contact page by going through the navigation link 'Contact Us' at the top of the page or they can obtain information straight away by going to the footer in place on every page, where it has become a standard practice to provide this information.

  2. As a returning visitor, I want to be able to gain quick access the artists' up-to-date work.
    1. The user can either visit the studios Instagram, which is represented by an icon on the footer of each page, or they can visit the 'Meet The Artists' page and go to the specific artists' instagram which is shown as a link under the artists' picture and introduction.

    [Returning User Story](documentation/testing/user-stories/returning-user-story-screenshot.png)

- #### Frequent Visitor Goals

  1. As a frequent visitor, I want to be able to see if any new artists have been added to the studio.
    1. Any new artists will be added to the list of artists on the 'Meet The Artists' page, which is self explanatory and would jump out at the user as being the first place to check.

### Further Testing
  All webpages have been validated against the W3 online validation sites which have come back with no errors or warnings, and I have checked compatibilities across various devices and a few different web browsers.

  Testing was carried out throughout the building of the website. I used Chrome developer tools whilst building help troubleshoot any issues I came across.

  I viewed each page of the website using google chrome developer tools to ensure that each page is responsive on a variety of different screen sizes and devices.

  - #### Full Testing

  ##### Home Page

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Site Mini Logo's | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| Navigation Links | Links direct user to appropriate page | Clicked each link | Each link takes user to correct page | Pass |
| Book In Button | Takes user to booking in page | Clicked on booking in button | Booking in page is loaded | Pass |
| Book In Button Hover Effect | Button turns to a darker shade of teal when user hovers over it | Hover over booking in button | Button shows correct colour when hovering over it | Pass |
| Laser By Stephania Logo/Button | Opens Laser by Stephania booking page in a new tab | Clicked on logo/button | A new tab opens and loads the correct page | Pass |
| Social Media Icons | Opens a new tab to each social media account for the studio | Clicked on each icon | A new tab opens and loads the correct pages | Pass |

  ##### Meet The Artists

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Site Mini Logo's | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| Navigation Links | Links direct user to appropriate page | Clicked each link | Each link takes user to correct page | Pass |
| Links for each artist | Opens each link in a new tab, email link opens new email in users default programme | Clicked on each link | Both webpage links open into a new tab displaying appropriate page and email opens a new email in Outlook | Pass |
| Laser By Stephania Logo/Button | Opens Laser by Stephania booking page in a new tab | Clicked on logo/button | A new tab opens and loads the correct page | Pass |
| Social Media Icons | Opens a new tab to each social media account for the studio | Clicked on each icon | A new tab opens and loads the correct pages | Pass |

  ##### FAQs

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Site Mini Logo's | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| Navigation Links | Links direct user to appropriate page | Clicked each link | Each link takes user to correct page | Pass |
| Question Button | Expands answer below when clicked | Clicked on each question button | Answers are displayed correctly below question | Pass |
| Question Button Hover Effect | Button turns to a lighter shade of teal when user hovers over it | Hover over each question button | Button shows correct colour when hovering over it | Pass |
| Laser By Stephania Logo/Button | Opens Laser by Stephania booking page in a new tab | Clicked on logo/button | A new tab opens and loads the correct page | Pass |
| Social Media Icons | Opens a new tab to each social media account for the studio | Clicked on each icon | A new tab opens and loads the correct pages | Pass |

  ##### Contact Us

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Site Mini Logo's | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| Navigation Links | Links direct user to appropriate page | Clicked each link | Each link takes user to correct page | Pass |
| Email the Studio Link | Link opens new email | Clicked on link | A new email is opened in Outlook | Pass |
| Laser By Stephania Logo/Button | Opens Laser by Stephania booking page in a new tab | Clicked on logo/button | A new tab opens and loads the correct page | Pass |
| Social Media Icons | Opens a new tab to each social media account for the studio | Clicked on each icon | A new tab opens and loads the correct pages | Pass |

  ##### Book In

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| Site Mini Logo's | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| Navigation Links | Links direct user to appropriate page | Clicked each link | Each link takes user to correct page | Pass |
| Buttons For All Email Links | Opens a new email to either studio or artists address | Clicked on each picture button | A new email opens in Outlook | Pass |
| Form | Once user has filled in all required inputs, ticked check box and pressed submit, user taken to thank you page | Filled in all text areas, ticked checkbox and clicked on submit button | Directs user to thank you page | Pass |
| Clear Form Button | Removes inputted text from all text inputs | Clicked on button | All information removed | Pass |
| Laser By Stephania Logo/Button | Opens Laser by Stephania booking page in a new tab | Clicked on logo/button | A new tab opens and loads the correct page | Pass |
| Social Media Icons | Opens a new tab to each social media account for the studio | Clicked on each icon | A new tab opens and loads the correct pages | Pass |


- #### Chrome DevTools Audit Report
  The Google Page-speed Services were used to assess the accessibiity of the project to ensure the site met expected accessible standards on desktop and mobile. The performance on my website could be better and this could be improved upon on future releases - the project scored highly in all other areas.

  [Lighthouse Result](documentation/testing/lighthouse-results.png)

- #### Browser Testing
  - The Website has been tested on Google Chrome, Safari, and Microsoft Edge.
  - The website was tested on my iPhone 12 mobile and 27" Microsoft PC devices. All other responsive testing was completed online.
  - Testing has been completed to ensure that all pages were linking correctly and external links opened in a new tab.


### Solved Bugs

| No   | Bug  | How I solved the issue |
| :--- | :--- | :--- |
| 1 | After reading that Bootstrap was not required for this project on the Slack channels I was trying to work without the bootstrap framework and found it extremely difficult to code a completely HTML and CSS hamburger menu ![CSS hamburger menu not working properly](/documentation/testing/css-hamburger-bug.png)| After speaking with my tutor, she suggested that I could use the bootstrap framework just for the menu and that would be acceptable for the project, I read the documentation on the Bootstrap navigation element and implemented this into my site |
| 2 | For the contact page, I wanted a map to be at the bottom of the content on that page and also for it to be responsive, I had placed an embedded map but it was only one size and did not look good within other device sizes | I typed my query into google and found a good [tutorial](https://www.w3schools.com/howto/howto_css_responsive_iframes.asp) on W3 schools which showed my how to style the class for the map|
| 3 | The font for the navigation links would not change to the particular font I wanted | I researched this and managed to find [this article](https://forum.squarespace.com/topic/253132-custom-css-not-overriding-font-styles-site-nav-links/) where I learnt about the !important attribute and fixed this issue. This attribute was then used for other elements |

### Known Bugs

* When testing was carried out on an Iphone 12 mobile, the booking in form does not display correctly; the title is off center, the checkbox is left aligned for some reason and users have to scroll to the right slightly to view the end of the text box. This is all displayed correctly when viewing on a desktop and reducing the screen size either just through the browser or through devtools.

  ![Form not displaying correctly](/documentation/testing/mobile-form-screenshot.png)

- - -

## Credits

### Code Used

* I used [This Tutorial](https://forum.squarespace.com/topic/253132-custom-css-not-overriding-font-styles-site-nav-links/) where I learned how to make css !important to over-ride other applied css styles.

* I read [Bootstrap documentation](https://getbootstrap.com/docs/4.3/getting-started/introduction/) to learn about the responsive navigation element, in order to make it change to the hamburger menu for smaller screen sizes than laptops.

* I utilised the [Flexbox Froggy](https://flexboxfroggy.com/) game in combination with [This Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) in order to teach myself how to use Flexbox.

* I used this [video tutorial](https://www.youtube.com/watch?v=N5wpD9Ov_To) on YouTube by [Kevin Powell](https://www.youtube.com/@KevinPowell) to ensure I was using the correct units within my css.

* I found [This Tutorial](https://stackoverflow.com/questions/31379175/bootstrap-button-on-click-showing-default-colour) which showed me how to change button colour once pressed, for the booking in button on the main home page.

* I used [This Tutorial](https://www.w3schools.com/howto/howto_js_collapsible.asp) to learn how to make collapsable questions on the FAQs page.

* I used [This Tutorial](https://www.w3schools.com/howto/howto_css_responsive_iframes.asp) to show a responsive sized map on contact us page.

### Content

All text content for the site has been pulled from the original website and all logo's were created by me.

### Acknowledgments

I would like to acknowledge the following people:

* Niclas_5P_Lead - On the Code Institute slack channels, who provided me with thorough help and advice.

* Tutor Support at Code Institute - Who provided me with guidance and learning materials, helpful hints and tips.

* Rachel Furlong - My college tutor, who maintained contact throughout the project and provided reassurance.

* Jubril Akolade - My mentor, who provided me with guidance and reassurance.

