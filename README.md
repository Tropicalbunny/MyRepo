# Visit Kent

---

Visit Kent is designed for people who would like to visit kent but are unsure about places to visit or what kent has avaliable.

## UX

---

### User Stories

The main end user goals is to find and visit highly rated locations in kent.

- I would expect clear direction to locations and what they have to offer
- I expect to be able to contact if i have any questions, or struggle finding something that suits me
- I would like simple design responces that show me where i am.
- as a user of the website i want to be able to find highly rated activites in kent

### Project Goals

The main project goal of this website is to make an easy, user friendly website for all ages. to achieve this, I have broken down the goals into achievable milestones.

- Make an incredibly simple UI so people that have less knowledge to technology can have a pleasant experience
- Clearly show locations, with images that peak intrest
-

### Busines Goals

The main business goal is to create a positive experience so consumers will frequently return.

- increase business traffic
- increase page rank and advertisement revenue

### Minimum Acceptance Criteria

- Easy access to different locations and what they have to offer
- Streamlined Experience
- User friendly across all devices

## Development

---

### Inital idea

![old website](assets/Readme-assets/oldwebsite.jpg "oldwebsite")

My original idea (above) i had started coding, but while developing i decided the user interface was messy and uninspired. which pushed me to go back to the drawing board and redevelop how i wanted the website to look and function. my biggest issue was Phone users wasnt in the forefront of my mind, and while coding i realised the website would easily become cluttered and akward to navigate, below are some brief descriptions of issues i had. (will not go into detail as re-development had its own issues)

- spacing issues with icons
- hover over changes issues
- aligning logo left without changing in nav bar
- reduction of hero image resolutions to fit. (will go into more detail below)

### Final Idea

![Flow diagram](assets/Readme-assets/FlowDiag.PNG "Flowdiag")

above is the basic function of the website, this is how i wanted the website to flow to each webpage.

![Figma design](assets/Readme-assets/Figma.PNG "Figma")

This was my re-design to make the website more user friendly, i also designed how i wanted the website to look on tablet and phone.

#### Notable Design Decisions.

i decided to move the Home link to the center of the navigation bar, this was due to the "locations" drop down list not sitting correctly under the link

I added Photos behind the location containers, i felt the site was a little bland. this made a sublte but big difference. (photo includes two with and two without)

![container chnages](assets/Readme-assets/Notable-change-containers.PNG "containerchanges")

####  Pre code Testing

used adobe color wheel to make sure contrast between text and background was acceptable.

#### During Code Testing

Checking and updating media querys to make sure structure is not comprimised when modifying code (see images below)

![media query broken](assets/Readme-assets/Checking-media-quieries-broken.PNG "brokenquery")
![media query fixed](assets/Readme-assets/Checking-media-quieries-fixed.PNG "fixedquery")

I had major issues with the Footer, the containers wouldnt align properly once they had their contents, after a re-code i managed to fix the issue
![footer broken](assets/Readme-assets/broken-footer.png "brokenfooter")
![footer fixed](assets/Readme-assets/Fixed-Footer.PNG "fixedfooter")

#### Final Testing

Release a beta for the website, given to people with various devices to check integrity and discover bugs.

#### Features implemented

* Slideshow gallery
* drop down list for locations
* underline links on hover
* bold and slight size increase of active navbar webpage

#### Planned Features

* Radius search
* trip-advisor search
* user reviews

### Technologies used

* HTML 5
* CSS 3
* JAVASCRIPT (through w3c schools gallery)

### Issues

#### Known bugs

#### fixed bugs

* odd blue lines hanging off fontawesome icons (solution: added Text-tranform: none)
* font awesome container offsets when set to display :inine; (rebuilt the footer fully)
* footer box 1 off center when shrinking (solved after footer rebuild)
* photos in 4k had to be reduced to 1080p for easier placement.
* nav bar wouldnt center with display: inline, used bootstrap to correct the issue.
* drop down list on locations off center, changed the layout of header to rectify.

## Credits

---

### Images
* pixabay (https://pixabay.com/photos/)
* Thomas Anderson, Hanne Jessen. for some stunning photos.

### Code aid
* Adegbenga Adeye (Mentor)
* Pasquale Fasulo (COBC Tutor)
* w3c schools for the Gallery (https://www.w3schools.com/html/)
* bootstrap v4.6 (https://getbootstrap.com/docs/4.6/)