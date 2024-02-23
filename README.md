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
    * [The Home Page](#the-home-page)
    * [The Game Page](#the-game-page)
    * [Future Implementations](#future-implementations)
  * [Accessibility](#accessibility)

* [Technologies Used](#technologies-used)
  * [Languages Used](#languages-used)
  * [Frameworks, Libraries & Programs Used](#frameworks-libraries--programs-used)

* [Deployment & Local Development](#deployment--local-development)
  * [Deployment](#deployment)
  * [Local Development](#local-development)
    * [How to Fork](#how-to-fork)
    * [How to Clone](#how-to-clone)

* [Testing](#testing)
  * [Solved Bugs](#solved-bugs)
  * [Known Bugs](#known-bugs)
  
* [Credits](#credits)
  * [Code Used](#code-used)
  * [Content](#content)
  * [Media](#media)
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

* #### Frequent Visitor Goals

        1. As a frequent visitor, I want to be able to see if any new artists have been added to the studio.

---

- ### Design

- #### Colour Scheme

  I initially chose a colour scheme of grey and pink but once I had applied the colours early on I decided that it did not work and did not provide the look I was going for. I then found a colour palette of shades of teal which I have used and also added to with selections of my own, complimented with gold accents, with black and white details to provide the necessary distinction between background and content.
  All colours are displayed within a commented section of my css so that if you need to change anything, you can make the changes in this section and it will apply to the classes, some of which cover repeated elements throughout the website.

  I have used #013636 for the background of the navigation and footer elements.
  Using a slightly lighter teal, #006666, for the background of all pages to distinguish the difference between header, footer and main section of the webpage.
  All text and icons are in white to ensure this is easily visible to the user.
  I have used #011d1d for the page titles, I made this a little darker, again to really make the text distinguishable.

![Black Rose Tattoo Colour Scheme](documentation/colour-palette.png)

- #### Typography
  Google Fonts was used to import the chosen fonts for use on the site.

  - For the Page Title I have used the google font [Pirata One](https://fonts.google.com/specimen/Pirata+One?query=pirata+one) Pirata One is a font that is close to black lettering which is a calligraphy style commonly used by tattoo artists.

  ![Pirata One Font Example](documentation/pirata-one-example.png)

  - I have also chosen [Montserrat](documentation/montserrat-example.png) as my other font, which is clear and easily readable.

- #### Imagery

  - This is an important aspect of this website as tattoo's are a visual commodity, images will showcase the studio and also examples of the artists work. The main image on the home page gives the user a sneak peak at the tattoo studio before setting foot in the physical location.
  - Any images used have been obtained with permission by the Studio owner.

- #### Wireframes

  - Home Page Wireframes [Desktop](documentation/wireframes/home-wireframe.png) [Mobile](documentation/wireframes/home-mobile-wireframe.png)
  - FAQ Page Wireframe [View](documentation/wireframes/faqs-wireframe.png)
  - Contact Us Page Wireframe [View](documentation/wireframes/contact-us-wireframe.png)
  - Booking In Page Wireframe [Desktop](documentation/wireframes/book-in-wireframe.png) [Mobile](documentation/wireframes/book-in-mobile-wireframe.png)

## Technology Used

This project is written using HTML & CSS using the Cloud IDE. I have also used flex-box and bootstrap to make the site responsive, and it is currently being hosted on GitHub.

HTML & CSS has been ran through the W3 Validators with no errors.

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

### Accessibility

I have been trying to make the project and website as accessible as possible. I have been doing this by:

* Using semantic HTML.
* Using the hover element on all buttons on the site to make it known to the user that they are hovering over a button.
* Making sure all pictures have an alt attribute.
* Ensuring that there is a enough colour contrast throughout the site and the background (and background image) does not distract from the content.

### Languages Used

- HTML5
- CSS3
- Javascript

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
   *[Am I Responsive?](http://ami.responsivedesign.is/) To show the website home page image on a range of devices.

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

<!-- ## Testing

Please refer to [TESTING.md](TESTING.md) file for all testing carried out.

### Solved Bugs

| No | Bug | How I solved the issue |
| :--- | :--- | :--- |
| 1 | An error was displaying in the console when next was clicked after the first question, stating that results wasn't defined. | Data was defined in the callApi(), so couldn't be accessed as it was in local scope rather than global scope. By defining data globally and then passing the data as a parameter into the getQuestion() in the nextQuestion() solved this. |
| 2 | The Questions being pulled in from the JSON have HTML entity characters that are not escaped and therefore display incorrectly with symbols in place of the correct characters. ![Characters not escaping correctly in the JSON data](documentation/characters-not-escaped.webp) | After a lot of research into escaping characters, I came across a post on slack that mentioned using innerHTML rather than innerText. Once I changed the answers to innerHTML the characters are now displaying correctly. |
| 3 | I have the local storage set up to save the final score as mostRecentScore. However when completing a game and submitting the team name the score added to the high scores section would be the previous score and not the most recent score. | After a lot of research to try and find out why this was happening I went over the code again and decided to see if I changed mostRecentScore in the scoreLog to score it would make a difference. By changing this, I have solved the issue and it now pulls the most recent score achieved. |
| 4 | Players were able to select an answer which would then display whether correct or incorrect. However they could still click on the answers which meant they could click all the answers to receive the points.| I researched a way to disable the buttons and initially found that I could use answer1.disabled = true; This worked, however it added quite a bit of code, as I had to add this for each button. Further research led me to find [this article](https://blog.revillweb.com/jquery-disable-button-disabling-and-enabling-buttons-with-jquery-5e3ffe669ece) which showed how to use jQuery and the class on the buttons to enable and disable them all at the same time. This then allows me to enable the buttons when a new question has been populated and once a selection has been made, the answer buttons are disabled until the user clicks next to advance onto the next question. |
| 5 | There was an issue with the data-correct not always being removed correctly from questions, which meant that incorrect answers were displaying as correct | I changed the way the data-correct attribute was removed from the answers, by using the same a for loop similar to what was used to add the data-correct attribute. I also changed the for innerText in the for loop to be innerHTML so that it was correctly reading the same as what was displayed on the button. |
| 6 | If a user selected an incorrect answer and the correct answer contained HTML entity characters (such as /&#(\d+);/g) the correct button styling would not be applied to the displayCorrectAnswer variable and a error would display in the console. This would then prevent the user from progressing in the quiz as the next button would not display for them to move on.![Bug 6](documentation/bug-6.png) | I adjusted line 161 to use innerHTML rather than innerText, however the issue persisted. I looked for an answer online but struggled to find anything that would help. I then reached out to Bim Williams on Slack who is an alumni on the course and asked to run the problem past him. He suggested adding a function that would decode the HTML entity and then apply that function within line 161. The function takes the HTML entity characters and replaces them with the correct characters. I will be researching this topic further in my spare time to gain a deeper understanding of it. |

### Known Bugs

* When viewing on screens that use touch rather than a cursor, the colour change for the answer button selected is not immediately obvious as the hover state remains on the button. If the user clicks away from the button the colour can then been seen.

  ![Touch Button Colour](documentation/touch-button-colour.gif)

* There is a a warning displaying in the console on the live page. This error seems to be because GitHub hosted pages disable googles 3rd party cookie alternative FLoC, which then throws this error. The error doesn't affect the site in any way.

  ![Console warning](documentation/interest-cohort-error.png)

* When friends tested the site they found that very rarely a game will get stuck on a question, and it will not populate a new question but the question no counter continues to increase. This issue only seems to be if a large number of games are played consecutively, possibly using up the questions in the API. I have not been able to replicate this issue to troubleshoot further.
  ![Question overloaded](documentation/questions-depleted.gif)-->

- - -

## Credits

### Code Used

* I used [This Tutorial](https://forum.squarespace.com/topic/253132-custom-css-not-overriding-font-styles-site-nav-links/) where I learned how to make css !important to over-ride other applied css styles.

* I read [Bootstrap documentation](https://getbootstrap.com/docs/4.3/getting-started/introduction/) to find out about the navigation element, in order to make it responsive.

* I played the [Flexbox Froggy](https://flexboxfroggy.com/) in combination with [This Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) in order to teach myself how to use Flexbox.

* I used this [video tutorial](https://www.youtube.com/watch?v=N5wpD9Ov_To) on YouTube by [Kevin Powell](https://www.youtube.com/@KevinPowell) to ensure I was using the correct units within my css.

* I used [This Tutorial](https://stackoverflow.com/questions/31379175/bootstrap-button-on-click-showing-default-colour) which showed me how to change button colour once pressed, for the booking in button on the main home page.

* I used [This Tutorial](https://www.w3schools.com/howto/howto_js_collapsible.asp) to learn how to make collapsable questions on the FAQs page.

* I used [This Tutorial](https://www.w3schools.com/howto/howto_css_responsive_iframes.asp) to show a responsive sized map on contact us page.

### Content

All text content for the site has been pulled from the original website and all logo's were created by me.

### Acknowledgments

I would like to acknowledge the following people:

* Niclas_5P_Lead - On the Code Institute slack channels, who provided me with thorough help and advice.

* The Code Institute Tutors who provided me with guidance and helpful hints and tips.

* Rachel Furlong - My college tutor, who kept an eye on how I was doing and provided reassurance.

