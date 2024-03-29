# Visit Kent

## User-centric Frontend development project

---

Visit Kent is designed for people who would like to visit kent but are unsure about places to visit or what kent has avaliable.

Live Site https://tropicalbunny.github.io/MyRepo/

## Table of content

- [UX](#ux)
  - [User stories](#user-stories)
    - [New User Goals](#new-user-goals)
    - [Returning User Goals](#returning-user-goals)
  - [Project Goals](#project-goals)
  - [Business Goals](#business-goals)
  - [Minimum Acceptance Criteria](#minimum-acceptance-criteria)
- [Development](#development)
  - [Inital Idea](#inital-idea)
  - [Final Idea](#final-idea)
    - [Notable Design Decisions](#notable-design-decisions)
  - [Testing](#testing)
    - [Pre code Testing](#pre-code-testing)
    - [During Code Testing](#during-code-testing)
    - [Final Testing](#final-testing)
      - [User Comments](#user-comments)
      - [Personal Testing](#personal-testing)
  - [Features implemented](#features-implemented)
    - [Nav Bar](#nav-bar)
    - [Landing Page](#landing-page)
    - [Location Pages](#location-pages)
    - [Contact us page](#contact-us-page)
    - [About us](#about-us)
  - [Planned Features](#planned-features)
  - [Technologies Used](#technologies-used)
  - [Issues](#issues)
    - [Known Bugs](#known-bugs)
    - [Fixed Bugs](#fixed-bugs)
  - [Deployment](#deployment)
    - [Process](#process)
    - [Enccounted Issues](#encounted-issues)
- [Credits](#credits)

## UX

---

### User Stories

The main end user goals is to find and visit highly rated locations in kent.

#### New User Goals

- I would expect clear direction to locations and what they have to offer
- I expect to be able to contact if i have any questions, or struggle finding something that suits me
- I would like simple design responces that show me where i am.
- As a user of the website i want to be able to find highly rated activites in kent

#### Returning User Goals

- Easily find other locations and information about them

### Project Goals

The main project goal of this website is to make an easy, user friendly website for all ages. to achieve this, I have broken down the goals into achievable milestones.

- Make an incredibly simple UI so people that have less knowledge to technology can have a pleasant experience
- Clearly show locations, with images that peak intrest

### Business Goals

The main business goal is to create a positive experience so consumers will frequently return.

- Increase business traffic
- Increase page rank and advertisement revenue

### Minimum Acceptance Criteria

- Easy access to different locations and what they have to offer
- Streamlined Experience
- User friendly across all devices

## Development

---

### Inital idea

![old website](assets/Readme-assets/oldwebsite.jpg "oldwebsite")

My original idea (above) i had started coding, but while developing i decided the user interface was messy and uninspired. which pushed me to go back to the drawing board and redevelop how i wanted the website to look and function. my biggest issue was Phone users wasnt in the forefront of my mind, and while coding i realised the website would easily become cluttered and awkward to navigate, below are some brief descriptions of issues i had. (will not go into detail as re-development had its own issues)

- Spacing issues with icons
- Hover over changes issues
- Aligning logo left without changing in nav bar
- Reduction of hero image resolutions to fit. (will go into more detail below)

### Final Idea

I designed the website with simplicity in mind, trying to create a logical and reasoned flow across all pages, the physical process of the webpage is the same whether it be tablet, desktop or phone.

![Flow diagram](assets/Readme-assets/FlowDiag.PNG "Flowdiag")

Above is the basic function of the website, this is how i wanted the website to flow to each webpage.

![Figma design](assets/Readme-assets/Figma.PNG "Figma")

This was my re-design to make the website more user friendly, this is where i also created how i wanted the webpage to look across several devices, so i could maintain structural and user-centric stability.
the colours i have used across the site:

color: #D93D4A;
color: #A41818;
color: #4A4646;
color: #A07171;
color: #FFFFFF;

Fonts:
For titles i have used: 'Cinzel', as a backup serif
For text i have used: 'Josefin Sans', as a backup sans-serif
I have used two fonts so i could create a sense of hirearchy across the site

#### Notable Design Decisions.

I decided to move the Home link to the center of the navigation bar, this was due to the "locations" drop down list not sitting correctly under the link, when testing i made sure to make this a focal point, i needed to confirm that it would not cause any issues with user experience. user experience was not affected by the change

I added Photos behind the location containers, i felt the site was a little bland. this made a sublte but big difference. (photo includes two with and two without)

![container chnages](assets/Readme-assets/Notable-change-containers.PNG "containerchanges")

## Testing

---

### Pre code Testing

used adobe color wheel to make sure contrast between text and background was acceptable.

### During Code Testing

Checking and updating media querys to make sure structure is not comprimised when modifying code (see images below) i used egde developer tools to help me identify and rectify any issues uncovered, this was a regular tool that i used.

![media query broken](assets/Readme-assets/Checking-media-quieries-broken.PNG "brokenquery")
![media query fixed](assets/Readme-assets/Checking-media-quieries-fixed.PNG "fixedquery")

I had major issues with the Footer, the containers wouldnt align properly once they had their contents, after a re-code i managed to fix the issue

![footer broken](assets/Readme-assets/broken-footer.png "brokenfooter")
![footer fixed](assets/Readme-assets/Fixed-Footer.PNG "fixedfooter")

### Final Testing

#### User Comments

- Capital letters on locations, and some incorrect spelling
- Overall easy to navigate
- Responsive design is a nice touch
- The website worked as i expected it too

Testers were on a variety of devices,

Iphone 13
Samsung s21 ultra
Iphone 11 Pro max.
Iphone 13 pro
Iphone 12

The webpage responded and ran as expected across all the above devices.

#### Personal Testing

- Checked each navigational link and confirmed they are working
- Checked the form links and notice they do not work since being deployed.
- Made sure all text and containers align as thye should.

I have used JigSaw w3c to validate my CSS, Passed all clear.

I have used w3c html validator to validate my HTML, i have uncovered a few issues (shown below)
and i have taken steps to fix them.

![W3C-code-issues-landing](assets/Readme-assets/W3C-code-issues-landing.JPG "W3C-code-issues-landing")

![W3C-code-issues-landing-fixed](assets/Readme-assets/W3C-code-issues-landing-fixed.jpg "W3C-code-issues-landing-fixed")

I used lighthouse to make sure my website is in working order, below is my score for desktop:
![Lighthouse test desktop](assets/Readme-assets/Lighthouse-test-desktop.jpg "Lighthouse Test Desktop")

Below is my score on phone: i was overall happy with this score as some server side decisions prevented me getting a higher score.
![Lighthouse test mobile](assets/Readme-assets/Lighthouse-test.jpg "Lighthouse Test Mobile")

## Features Implemented

The website consists of 8 pages, 6 are accessable from the navigation bar, while one is an about us page accessable from the footer, the other is a success page after subbmitting the contact us form.

### Nav Bar

The Navigation bar consits of 3 parts, the first being location drop down menu, consiting of the 4 locations i have chosen. the next is a link to the home page, the logo also links to the home page, the final is a link to the contact us page.

### Landing Page

This page neded to be the most appealing of the page, when people come to my website i want them to stay and see what i have to offer,
so i selected a hero image that would grab attention.
then below this i have my 4 chosen locations that i hyperlinked to their respective pages

### Location Pages

These pages hold the galleries to showcase their respective locations, 4 of these pages have been made.
i kept the design simple and intresting, holding 3 images and text about the location

### Contact us page

this page i also kept simple, i centralised the form over a background so i had little wasted space

### About us

Simple page using a mix of the location page and landing page. simple text showing off me.

- Slideshow gallery
- Drop down list for locations
- Underline links on hover
- Bold and slight size increase of active navbar webpage

## Planned Features

- Radius search
- Trip-Advisor search
- User reviews

## Technologies Used

- HTML 5
- CSS 3
- JAVASCRIPT (through w3c schools gallery)
- Bootstrap v4
- Font awesome
- Google fonts
- Github
- gitpod
- Figma for design

## Issues

### Known Bugs

To my best knowledge i have crunched down all bugs i have found

### fixed Bugs

- Odd blue lines hanging off fontawesome icons (solution: added Text-tranform: none)
- Font awesome container offsets when set to display :inine; (rebuilt the footer fully)
- Footer box 1 off center when shrinking (solved after footer rebuild)
- Photos in 4k had to be reduced to 1080p for easier placement.
- Nav bar wouldnt center with display: inline, used bootstrap to correct the issue.
- Drop down list on locations off center, changed the layout of header to rectify.

## Deployment

---

### Process

Process for deploying a front end website was fairly easy. as i have all my commits and main branch on Gitpod it made the most sense to deploy on there as well, i used their deployment Gitpod Pages.

The Deployment of the project was as follows:

- Use this link https://github.com/Tropicalbunny/MyRepo to get to my repo, login as yourself and click code
- Clone a copy for yourself
- Once you have a copy, head to settings on the navigation bar.
- Under code and automation, click pages
- You change source to "deploy from branch"
- The branch will be "main" and "/root" you then click save.
- The deployment process can take a few minutes, let this complete you can see the progress on the code page under Enviroments.

### Encounted Issues

Galleries havent Deployed correctly. the images come up with error message 404 not being found. a little playing around and i found that the issue was the directories, in the preview the directories only worked a specific way, now its delpoyed i had to change them back to link

![gallery broken](assets/Readme-assets/gallery-deployment-issue1.PNG "broken gallery")

![gallery fixed](assets/Readme-assets/gallery-deployment-fixed.PNG "fixed gallery")

## Credits

---

### Images

- Pixabay (https://pixabay.com/photos/)
- Thomas Anderson, Hanne Jessen. for some stunning photos.

### Code aid

- Adegbenga Adeye (Mentor)
- Pasquale Fasulo (COBC Tutor)
- W3C schools for the Gallery (https://www.w3schools.com/html/)
- Bootstrap v4.6 (https://getbootstrap.com/docs/4.6/)

### Testing

- My Team At PML
- Family Programmers
