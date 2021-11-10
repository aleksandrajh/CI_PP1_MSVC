# Moss Side Volleyball Club <img src="assets\images\msvc-logo.png" style="width: 40px;height:40px;">


Developer: Aleksandra Haniok

![Responsible mockup of the website]()

Live webpage
<https://aleksandracodes.github.io/CI_PP1_MSVC/>

## Table of Content

## Project Goals

### User Goals

- Find a local volleyball club that offers training sessions for beginners where you can learn basic volleyball skills
- See the timetable of volleyball sessions
- Find a local team to compete in the volleyball league
- Find the location of sports venues where training sessions take place
- Enquire more information about the trainings and club
- Express interest and joining local community in playing volleyball

### Site Owner Goals

- Promote volleyball in the local area
- Promote the club
- Encourage people to start playing volleyball
- Provide essential information about the training sessions
- Obtain new players to the competitive team

## User Experience

### Target Audience

- People looking to learn to play volleyball
- People looking to come back to volleyball after not playing for a long time
- People willing to find a club which takes part in the local competition

### User Requirements and Expectations

- Quickly and easily find the relevant information
- Simple navigation around website
- Visually appealing design for all screen size
- Links and functions that work as expected
- An easy way to contact the club
- Accessibility

### User Stories

#### First-time users

1. As a first time user, I want to find out more about the club
2. As a first time user, I want to find out if I can join the club if I have never played volleyball before
3. As a first time user, I want to know if the club takes part in the local competition
4. As a first time user, I want to get a feeling of the club
5. As a first time user, I want to be able to contact the club with a specific question
   
#### Returning visitor

6. As a returning user, I want to see pictures from the recent club tournaments
7. As a returning user, I want to know who joins the social sessions
8. As a returning user, I want to find the club on social media
9. As a returning user, I want to know the training sessions times
10. As a returning user, I want to get direction to the sports venues

#### Site Owner

11.	As the site owner, I want user to get to know the club
12.	As the site owner, I want user to be able to contact us
13.	As the site owner, I want users to join the training sessions
14.	As the site owner, I want my site to be responsive
15.	As the site owner, I don’t want users to use browser back button if they’re searching for a page which does not exist.

## Design

### Colour

For the colour scheme a combination of black, dark red and white were chosen to match the club's logos. These colours and their shades were used throughout each section in such a way to ensure the contrast between them was right.

### Fonts

Architects Daughter with cursive as fallback was used for the logo and headings to give a bit of fun and relax feeling of the club.
Poppins with sans-serif as fallback was used for the body to present the content in clear and legible way.

### Structure

The website is structured in a user friendly and easy to learn way. At the top of the page the user can see a recognisable type of navigation bar with the club logo and name on the left side and the navigation links to the right which collapse to hamburger icon on smaller screen sizes. 

The website consists of four sections:

- A landing (home) section with a navigation bar and hero images on a carousel
- An about section with the information about the club
- A gallery with images from social volleyball trainings and local league games giving a general feel of the club
- A contact section with a contact form, location maps of two sports venues and information how to find the club

At the bottom of the page there is a footer with links to social media and copyrights info.

A separate 404 error page was created.

### Wireframes

<details><summary>Big screens - laptop & desktop</summary>
<img src="docs/wireframes/wireframes-home-and-about-laptop.JPG">
<img src="docs/wireframes/wireframes-gallery-laptop.JPG">
<img src="docs/wireframes/wireframes-contact-laptop.JPG">
</details>
<details><summary>Medium screens - tablets</summary>
<img src="docs/wireframes/wireframes-tablet.jpg">
</details>
<details><summary>Small screens - mobile</summary>
<img src="docs/wireframes/wireframes-mobile.jpg">
</details>

## Technologies Used

### Languages

- HTML
- CSS

### Frameworks & Tools

- Balsamiq
- Bootstrap v5.1.3
- Favicon.io
- Font Awesome
- Git
- GitHub
- Google Fonts
- Pixabay.com
- Remove.bg
- Visual Studio Code

## Features

The website consists of four sections and nine features.

### Logo and Navigation Bar
- Featured on the main website and the 404 error page
- The logo takes user to the main website home screen
- The nav bar contains links to Home screen (top of website), About section, Gallery section and Contact section.
- The nav bar is fully responsive and changes to a toggler (hamburger menu) on smaller size screens
- The navbar allows user to easily jump to a specific section on the website

![Logo and navbar](docs/features/feature-logo-and-navbar.JPG)
![Logo and navbar](docs/features/feature-logo-and-navbar-hamburger.JPG)

### Carousel
- Created based on Bootstrap framework.
- User is presented with three pictures from the club which give them a friendly feeling of the club.
- The headings over the pictures are to make the user welcomed on the website and encourage them to join the club
- The pictures slide automatically but user has the option to change the pictures via back and forward arrows or indicators at the bottom

![Carousel](docs/features/feature-carousel.jpg)

### About Section
- Provides a general description of the club
- Describes the social volleyball and local league competition
- Presents user with two club logos
- Provides information about training times, cost and locations
- User stories covered: 1, 2, 3, 7, 9, 11, 13

![About](docs/features/feature-about.jpg)
![About](docs/features/feature-about-2.jpg)

### Gallery Section
- Selection of images from social volleyball training and events
- Selection of images from local volleyball competition
- Each image slightly enlarges when hovered
- User stories covered: 4, 6, 7

![Gallery](docs/features/feature-gallery-social.JPG)
![Gallery](docs/features/feature-gallery-league.JPG)

### Quote
- An insprational and motivational volleyball quote to intrigue users about this sport

![Quote](docs/features/feature-quote.JPG)

### Contact Form
- Enables user to contact the club with a specific question or express interest in joining the club.
- User stories covered: 2, 5, 12

![Contact Form](docs/features/feature-contact-form.JPG)

### Maps
- Provides user with directions to the sports venues
- User stories covered: 10

![Maps](docs/features/feature-maps.JPG)

### Info
- Provides user with sports venues addresses and contact email
- User stories covered: 5, 10
  
![Info](docs/features/feature-info.JPG)

### Footer
- Featured on the main website and the 404 error page
- Contains links to social media, opening in a separate window
- Contains copyrights info
- User stories covered: 8

![Footer](docs/features/feature-footer.JPG)

## Validation

### HTML Validation

The W3C Markup Validation Service was used to validate the HTML of the website. All pages pass with no errors or no warnings to show.
<details><summary>All site</summary>
<img src="docs/validation/validation-html-site.jpg">
</details>

<details><summary>404 error page</summary>
<img src="docs/validation/validation-html-404page.jpg">
</details>

### CSS Validation

The W3C Jigsaw CSS Validation Service was used to validate the CSS of the website.
When validating all website, it passes with no errors found. However, some warning are identified linked to Bootstrap v5.1.3. 
When validating my own internal CSS, the validator shows no errors and one warning associated with vendor extension (-webkit-appearance).

<details><summary>All site</summary>
<img src="docs/validation/validation-css-all-site.jpg">
<img src="docs/validation/validation-css-all-site-2.jpg">
</details>
<details><summary>Internal stylesheet</summary>
<img src="docs/validation/validation-css-style.jpg">
</details>

## Testing

### Accessibility

The WAVE WebAIM web accessibility evaluation tool was used to ensure the website met high accessibility standards. All site pass with 0 errors.

<details><summary>See evaluation summary</summary><img src="docs/validation/validation-accessibility-all-site.jpg">
</details>

### Performance

Google Lighthouse in Google Chrome Developer Tools was used to test the performance of the website.
<details><summary>See evaluation summary</summary><img src="docs/validation/validation-lighthouse-performance.jpg">
</details>

### Performing tests on various devices

The website was tested using Google Chrome Developer Tools Toggle Device Toolbar to simulate viewports of different devices. 

The website was tested on the following devices:
- Lenovo B590 (laptop screen size)
- Samsung Galaxy Tab A (tablet screen)
- Samsung S7 (mobile screen)

### Browser compatability

The website was tested on the following browsers:
- Google Chrome
- Mozilla Firefox

### Testing user stories

1. As a first time user, I want to find out more about the club
2. As a first time user, I want to find out if I can join the club if I have never played volleyball before.
3. As a first time user, I want to know if the club takes part in the local competition

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| About Section | Navigate to the About section | Find description of the club. | Works as expected |

| About Section, Social Volleyball | Navigate to the About section | Description tells the user they can join with no previous experience | Works as expected |

| About Section, Local League | Navigate to the About section | User is provided with information about the MSVC League Teams, experience required and structure of trainings | Works as expected |


<details><summary>Screenshot</summary>
<img src="docs/user-story-testing/user-story-1-2-3.JPG">
</details>

4. As a first time user, I want to get a feeling of the club

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Gallery Section | Navigate to the Gallery Section | View pictures of the social volleyball sessions and local league teams | Works as expected |


<details><summary>Screenshot</summary>
<img src="docs/user-story-testing/user-story-4-6.JPG">
</details>

5. As a first time user, I want to be able to contact the club with a specific question

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Contact Form | Navigate to the Contact Section, fill out and submit contact form | Data submited via contact form | Works as expected |

<details><summary>Screenshot</summary>
<img src="docs/user-story-testing/user-story-5.JPG">
</details>

6. As a returning user, I want to see pictures from the recent club tournaments

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| Gallery Section | Navigate to the Gallery Section | View pictures of the social volleyball sessions and local league teams | Works as expected |

<details><summary>Screenshot</summary>
<img src="docs/user-story-testing/user-story-4-6.JPG">
</details>

7. As a returning user, I want to know who joins the social sessions

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
|-------------|------------|---------------------|-------------------|
| About Section | Navigate to the About Section | See description of Social Volleyball | Works as expected |
| Gallery Section | Navigate to the Gallery Section | View pictures from the social volleyball trainings and tournaments | Works as expected |

<details><summary>Screenshots</summary>
<img src="docs/user-story-testing/user-story-7a.JPG">
<img src="docs/user-story-testing/user-story-7b.JPG">
</details>






## Bugs

| Bug | Fix |
| ----------- | ----------- |
| Some bug | The fix for it |
| Paragraph   | Text        |
| Another bug   | How I fixed it |
| Yet another bug | How I fixed them  |

## Deployment

## Credits

## Acknowledgements
