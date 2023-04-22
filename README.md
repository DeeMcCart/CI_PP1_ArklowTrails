# Arklow Walking Trails 
(Developer:  Deirdre McCarthy)

# Table of Contents:
1. [About](#about)
2. [Project Goals: ](#project-goals)
  1. [UX Design - Strategy ](#ux-design-strategy) 
  2. [UX Design - Strategy - Competitor Portals](#ux-design-strategy-analysis-of-competitor-offerings)
  3. [UX Design - Strategy - Target Audience](#ux-design-strategy-target-audience)
3. [UX Design - Scope](#ux-design-scope)
    1. [UX Design - Scope - User Requirements and Expectations](#ux-design-scope-user-requirements-and-expectations)
    2. [UX Design - Scope - Data](#ux-design-scope-data)
    3. [UX Design - Scope - Viewing Device](#ux-design-scope-viewing-device)
4.[User goals/ user stories: ](#user-goals-user-stories)
  1.  [Site Owner Goals](#site-owner-goals)
  2.  [First-time User Goals](#first-time-user-goals)
  3.  [Returning User Goals](#returning-user-goals)
  4.  [Other stakeholder Goals](#other-stakeholder-goals)
  5.  [Future Site owner and Administrator Goals](#future-site-owner-and-administrator-goals)
6.  [Further UX Design: ](#ux-design-decisions)
  1. [Structure - Checklist](#structure)
  2. [Skeleton - Wireframes; ](#wireframes)
  3. [Surface - Fonts; ](#fonts-chosen) 
  4. [Surface - Colours](#colour-scheme)
  5. [Surface - Imagery](#design-images)
7. [Features](#features)
  1. [Included](#features-in-scope)
  2. [Future Development](#features-left-to-implement)
  3. [Requirements Tracing](#RTM)
4. [Technology](#technologies)
  6.1  [Languages](#langugages)
  6.2  [Frameworks and Tools](#frameworks--tools)
14. [Testing](#testing)
  7.1 [Testing against Requirements](#rtm-proof)
  7.2 [Validator testing](#validator-testing)
  7.3 [Manual Testing](#manual-testing)
    7.4 [Multi-device Testing](#multi-device-testing)
    7.5 [Multi-browser Testing](#multi-browser-testing)
    7.6 [Unfixed Bugs](#unfixed-bugs)
15. [Accessibility](#accessibility)
16. [Performance](#performance)
17. [Deployment](#deployment)
18. [Credits](#credits)
  11.1 [Content](#content)
  11.2 [Media](#media)
  11.3 [Acknowledgements](#acknowledgements)

## About
---------
This website highlights jogging, hiking and walking trails available in the Arklow, Co. Wicklow area of Ireland.  It is designed for recreational runners and walkers, which may include tourists (First-time and Returning site visitors), and local people (typically Returning site visitors).   
The site is intended to raise awareness of Arklow's community walking routes, to highlight the natural and urban landscape of Arklow, and, as a tourism aid, to showcase some of the pleasant and interesting features within Arklow Town.  Site visitors are invited to participate in developing the site by contributing their own feedback and photos.  
<br>
The site exists primarily to showcase available walking/jogging trails, to make people aware of the facilities available on each trail, and to assist them in navigating independently to a starting point.

Notice that the images on this website show trails, landscapes, animals and objects rather than people.  The intention is to focus largely on the trails, thus encouraging independent access to the routes.  Visitors are made aware of, and invited to participate in, the informal Trail Trotter runs/ walks (facebook link in footer).

### Responsive Mockup
https://ui.dev/amiresponsive?url=https://deemccart.github.io/CI_PP1_ArklowTrails/

### Live webpage link
https://deemccart.github.io/CI_PP1_ArklowTrails

## Project Goals
----------------
To produce a user-friendly, informative website of walks and trails in the Arklow geographical area.
### UX Design Strategy
The aim of this specific website is to increase the 'brand awareness' of Arklow as an active tourism destination.
This website also acts as a 'proof of concept' for a re-usable location-focussed walks site which can be re-configured for individual localities and paired with Google maps data for walks in those localities.
<br>
While the site as implemented stands indepdendently, potentially this is an offshoot of the Wicklow Tourism, Failte ireland or other partner website.
<br>
The audience is:<br>
a. Tourists visiting the locality, who wish to explore the area on foot<br>
b. Local residents who wish to explore the area <br>
Note that both these groups may have varying mobility capabilities, and therefore it is important to flag if certain routes are wheelchair/ pushchair friendly.
c. Groups on school tours or day outings who are seeking (possibly guided) walks 

### UX Design Strategy Analysis of Competitor Offerings
Existing walking guide sites covering this locality include:<br>
https://www.alltrails.com/ireland/county-wicklow/arklow <br>
https://www.visitarklow.ie/nature-outdoors/walks<br>
https://www.visitarklow.ie/post/4-family-friendly-trails-in-arklow-town-great-for-a-walk-cycle-or-scoot<br>
https://www.visitarklow.ie/post/arklow-town-heritage-walks<br>
https://www.coillte.ie/site/glenart-wood/<br>
https://www.sportireland.ie/outdoors/walking/trails/<br>

A competitive analysis of these offerings can be seen here https://deemccart.github.io/CI_PP1_ArklowTrails/assets/readme_images/Strategy-competitive-analysis.pdf
<br>
From this analysis, a set of possible requirements was identified for a new portal.

In summary, while each of these portals reviewed promotes one or more walks, the data is scattered and inconsistent.  Maps are formatted differently on each site (or, worse still, only available behind a paywall).  It can be very difficult for a non-local user to interpret or relate to the maps given, as they are topographical rather than street-feature based.  In some cases, routes are advertised as being within the town, which in fact are some distance away.  It is difficult, without local knowledge, to evaluate whether a walk is accessible and available to particular groups of users.
<br>
Few of the available websites facilitate independent navigation to the walk routes.  None of the existing sites includes the full range of available trails, and portals don't consistently include actual route maps and parking information.
<br><br>
While the competitor research was done by targeting a particular geographic location - Arklow - the problem of difficult-to-find or inaccessible walks data exists throughout Ireland.  Multiple providers are offering parts of a solution, and each has their own approach to mapping with varying degrees of usability.  For a user to find the available walks in a particular area, they would need to first be aware of organisations that might have an offering (Coillte, Sport Ireland, Wicklow Tourism etc).  This in itself requires a certain familiarity with Irish public bodies.  The user must then navigate the quirks of individual portals to arrive at a mapped offering which might not need their needs (e.g. sophisticated hiking map offered to recreational walker ). 
<br>
<br>
The Arklow Trails website therefore proposes to provide a portal whereby standard Google Maps functionality (including navigation) is made available to the end user, and the Google Map acts as an entry point to a database of walks presented on this website.   This solution is intended to be scaleable and could be adopted as a standardised portal which can be linked to by multiple partner organisations (Wicklow County Development, Wicklow Local Authorities, Historical Societies, and so on).  It is intended that users can navigate the site access information easily, without incurring stress or frustration.
<br>

### UX Design Strategy Target Audience
* The target audience includes visitors to, and residents of, Arklow who seek running/walking route information
* The target audience includes recreational walkers, joggers and hikers, alone or in groups.
* Runners are a particular target audience, and would like to know route difficulty level?
* Family groups are a particular target audience, perhaps including mobility challenges - suitability for pushchairs/wheelchairs
* Dog walkers?

## UX Design Scope
----------------

### UX Design Scope User Requirements and Expectations
The basic requirement for users is to access a usable website that provides information and mapping for a range of trails.

* The target audience seeks assistance to choose an appropriate walk (terrain, distance, safety, accessibility) for their needs
* The target audience may have an interest in local history and wish to learn more via website links (possibly a future enhancement)
* The target audience wishes to know about teashops/ bathrooms en route

### UX Design Scope Data
The Arklow Trails website, as implemented, features 6 walking trails within a certain geographical locality (Arklow town).
Mapped Trail start points (Google maps points-of-interest) and routes (Google maps polylines) are provided. 
Standardised categories (distance, features, terrain) are applied to each walk, and a narrative description is held for each.
A range of associated photos per walk is to be provided. 

### UX Design Scope Viewing Device 
* NB  The target audience are likely to commence using the site on desktop, and then to progress to small-screen use.
<br>
They will use this site when they are 'out and about' to:
* locate the start of the walk relative to their current location, 
* (possibly) cross-reference site photos against what their obervations when walking one of the routes
* add new photos and reviews, which increase the bank of knowledge about this walk.  
Therefore the primary site usage is expected to be via mobile devices.
Support for a range of device types, and responsiveness to the size of the user's screen are highly important for the successful implementation of this website

## User Goals/ User Stories
----------------

### Site owner Goals
* As site owner I want to list five (or more) key walks in the Arklow area
* As site owner I want to categorize walks to allow users to choose the most appropriate for their needs
* As site owner I want to provide a google maps link to the location of each of the walks
* As site owner I want to provide an attractive gallery of images which encourage outdoor pursuits in this locality
* As site owner I want to raise awareness of local sightseeing items
* As site owner I wish to promote responsible dog walking (doggie poop bins)
* As site owner I wish to showcase local hospitality business - cafes and tea shops en route 
* As site owner I wish to promote community engagement by encouraging users to leave reviews and photos of their walk own experience
* As site owner I want to encourage awareness of community sponsors including: Arklow Tidy Towns, Arklow Municipal District, Wicklow Sports Partnership, Arklow Maritime Musemu, Arklow Historical Society

### First-time User Goals
* As a first-time user I want to see what trails are available within a geographic area
* As a first-time user I want to see how long a trail is, and how difficult (gradient, terrain) it is
* As a family user I want to know whether it is suitable for pushchairs or young children
* As a first-time user I want to see attractive pictures (to motivate me and others to select a particular trail)
* As a first-time/ family/ recreational user I would like to know what rest/food facilities are available on the route
* As a first-time user I would like to understand how to reach the start point from my current location   
* As a first time user I would like to be able to navigate the site and quickly learn its functionality

### Returning User Goals
* As a returning user I would like to be able to navigate the site easily and to 'drill into' selected walks
* As a returning user I would like to be able to navigate the sites on my mobile device when 'out and about'
* As a returning user I would like to be able to view photo gallery for individual walks
* As a returning user I would like to locate the start of a walk relative to my own location
* As a returning user I would like to have a facility to upload my walk photos and add reviews/comments
* As a returning user I would like to be able to suggest other walks of interest and upload information for consideration by the site owners

### Other stakeholder Goals
* As a local restaurant/cafe/shop owner, while I don't plan to use the site myself, I would like my business to be promoted as a stop-off
* As a local litter warden I would like people to be aware where the doggie poop bins/ bag stores are located
* As the local Tidy Towns co-ordinator I would like to promote certain walks where we want to increase foot traffic thereby reducing anti-social activity

### Future Site owner and Administrator Goals
* NB In the future, the current site owner role may evolve into two roles - Site Owner and Site Administrator.  One or more Site Administrators would take on the roles listed above for specific geographic territories, and a new Site Owner role with overall responsibilities for hosting a bank of trails websites (and possibly for digitising new walks at the site Administrators request)    
* In order to process user feedback, a future rule of site moderator (Administrator) will be needed to review and approve submitted reviews and photos, and add them to the trails website databank.

## UX Design Decisions
----------------

### Structure

The key goals of UX design - structure plane - are addressed as follows:<br>

https://deemccart.github.io/CI_PP1_ArklowTrails/assets/readme_images/UX-structure-plane.jpg



### Wireframes
<details><summary>Landing Page</summary>
The landing page WF is shown here with 4 sceen resolutions as I found when testing that the Motorola G(7) was truncating to the right hand side for 2-column pictures display, therefore I added an additional responsiveness section to cater for 320-400 pixel screen size.
  
<img src="https://deemccart.github.io/CI_PP1_ArklowTrails/assets/readme_images/WF01-landing-page.jpg">
</details>

<details><summary>Walk Details</summary>
<img src="https://deemccart.github.io/CI_PP1_ArklowTrails/assets/readme_images/WF02-Walk-Details.jpg">
</details>

<details><summary>Gallery</summary>
<img src="https://deemccart.github.io/CI_PP1_ArklowTrails/assets/readme_images/WF03-gallery.jpg">
</details>

<details><summary>Feedback</summary>
<img src="docs/wireframes/WF04-feedback.jpg">
</details>





### Fonts Chosen
Libre Franklin and Libre Baskerville are chosen because they are readable on large screens or smaller mobile devices.  This font is recommended for sites that may be content-heavy but which are regarded as fun friendly and approachable/inclusive.  These are identified by Google as good pairing.

In practice, these fonts DO look readable and businesslike, but don't look particularly  friendly or approachable... therefore an improved font would be less formal (sans serif???)

### Colour Scheme
The colour combinations chosen are ...
blue-green, light-blue, ice-cream yellow.... the overall to resemble neapolitan ice cream which is a visual trigger for Arklow as a seaside town.
These colours also represent forest, water - river and sea, and sand - these are typical landscapes covered by the walks shown, as Arklow is a coastal town sited in a river valley and giving access to large stretches of rocky coastline.

 The colours used are non-threatening and feel friendly, familiar and safe, so encouraging to users who may be socially hesitant,  or feel embarassed about their level of fitness, to feel that the Arklow Trails are inclusive, friendly and will welcome them.

### Design Imagery
The images chosen is reminicent of .....
ice cream
1970's seaside visits
slightly faded postcard photos ... retro feel to bring people back into safety of childhood.

## Features 
* Different parts of your project, and describe each in a sentence or so. 
* Explain what value each of the features provides for the user, 
* focusing on who this website is for, 
* what it is that they want to achieve and 
* how your project is the best way to help them achieve these things.
 
### F01 Google Maps used as the anchor image on the landing page
![Landing Page showing Google Map at centre](./assets/readme_images/230418%20Landing%20Page.jpg?raw=true "Landing Page")
![Landing Page showing Google Map at centre](./assets/readme_images/F01-Feature-Google-Map-as-main-image-on-screen?raw=true "Landing Page")
![Landing Page showing Google Map at centre](./assets/readme_images/F01-Feature-Google-Map-as-main-image-on-screen-tablet-mode?raw=true "Landing Page")
The use of Google Map was a deliberate design decision. Google maps is widely used (by people of all demographics) as a navigation tool.  It's familiarity reduces the overall learning curve for new users of the Arklow Trails website.  

### F02 Color-coded mapped walks
Six colour-coded mapped trails are shown.  The range of colours means they can be clearly distinguished from one another, and the same colour is used in the flipcard boundary.  
![Six colour-coded walks on Google Maps background](./assets/readme_images/F02-Feature-colour-coded-walks.jpg?raw=true "Mapped Walks")
![Colour-coded walks Google Maps large screen](./assets/readme_images/F02-Feature-Google-Map-maximised-to-show-walk-data.jpg?raw=true "Colour-coded walks Google Maps large screen")

### F03 Colour-edged Photo Flipcards
The landing page map is surrounded by colour-edged flipcards, one per walks.
The border colour of each flipcard corresponds to the #rgb colour of its associated trail.
Each flipcard shows an attractive or intruiging photo, encouraging the user to hover over the image trail information.

![Flipcard attractive photo example](./assets/readme_images/F03_a-Flipcard-images-photos.jpg?raw=true "Flipcard Attractive Photo").

On larger screens the flipcards are positioned to the left and the right of the main map.  On smaller screens, the main map appears first, with the flipcards appearing in either two, or, at smallest, one column below the map.

Hovering over a walk card 'flips' the display to show a walk name and summary detail.

### F04 The colour-edged photos flip to reveal walk summary
If the user's mouse moves over (desktop) or clicks (mobile) a colour-edged photo, it performs a pleasing shimmy and reveals summary trail data.
The user can then select a 'More details' link to access a point within the detailed 'Walks' page:
  - Each card identifies the walk by name and some key features of each walk.
  - Clicking on a particular card opens a link to the relevant walk detail  

- Icons are used within the category cards to categorise distance, trail type (forest/nature/seaside) etc..... 
- The consistent and repeated use of certain icons aids user learning 
- The use of icons improves readability and navigation, particularly for returning users

![Flipcard walks summary card](./assets/readme_images/F04_b-Flipcard-images-walk-summary.jpg?raw=true "Flipcard Attractive Photo")

Standard symbols are used for walk categorisation e.g. birds, sea, swimming, river, forest:

![Flipcard walks summary with category symbols](./assets/readme_images/F04-Feature-Fipcard-use-of-categorisation-icons.jpg?raw=true "Flipcard summary with category symbols")

Each flipcard has a 'More details...' link to encourage the user to access the walk details page:

![Flipcard walks summary more details link](./assets/readme_images/F04-Feature-Flipcard-More-Details.jpg?raw=true "Flipcard summary with link to more details")

### F05 More details for each trail
The user can see more details per trail in one of three ways:
* By clicking on the 'more details' link from a flipcard (link to more details for a specific trail)
* By clicking on the URL linked to each trail in Google Maps (link to more details for a specific trail)
* Using the navbar to go directly to the 'Walks' page and scroll to find a walk of interest

Note that there are hyperlinks within page to position at each walk (walk01, walk02, etc )

![More details of a walk](./assets/readme_images/F05-Feature-Walk-Details-Page.jpg?raw=true "More details of a walk")

### F06 Feature consistent icons and categorisation
As per the walks summary flipcard the same symbols are used to help with learning the website
![Consistent Use of icons and categories](./assets/readme_images/F06-Feature-Walk-Details-use-of-categorisation-icons.jpg?raw=true "Icons and categories walks detail")
- clicking on a walk card brings the user to a separate walk details window which provides more information on each walk.  
- an explanation of the icons and categories is given on the 'About' page
![WalkCatCards](image3.png)
![HelpIconCategories](image4.png)

### F07-Average Reviews stars
Feature average reviews
![Average trail reviews per walk](./assets/readme_images/F07-Feature-Walk-Details-average-trail-reviews.jpg?raw=true "Average trail reviews stars out of 5")

### F08 Walk Details Descriptive text
Helpful descriptions to describe the walk and help the reader determine if it is suitable or of interest to them.
![Six colour-coded walks on Google Maps background](./assets/readme_images/F08-Feature-Walk-Details-descriptive-text.jpg?raw=true "Mapped Walks")

### F09 Image carousel
An animated gallery of images is available per walk.
This is a simple html/css animation using a deck of 4 photos per walk with the viewing window transitioning between them.
(This became more complex to implement when I realised that the animation must be iniated by the user rather than auto-play).
![A clickable image carousel is shown](./assets/readme_images/F09-Feature-album-carousel.jpg?raw=true "Image carousel")

### F10 Responsive Navbar
The navigation bar appears on all pages, and is attractively laid out.  Four links are available - Home - Walks - Gallery - Feedback
The navbar is visible at the top of each screen, and is identical in each page/ screen size combination to allow for easy navigation.
It is fully responsive so will change positioning at 320, 400, 800 pixel screen widths. 
This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button.

![Responsive navbar](./assets/readme_images/F10-Feature-Navbar.jpg?raw=true "Responsive navbar")


### F11 Partner social media links (footer)
As this website is structured to operate more like to a peer-to-peer than a hierarchical structre, the footer bar is not currently used for broadcasting from a single site owner's social links, instead it is a set of 'partner' links to groups or websites which are relevant.  Currently configured to point to:
* Social media/fabebook - Arklow Trail Trotters walking group, with details of their meeting times.
* Visit Wicklow website
* generic youtube
* generic instagram
![Footer partner links](./assets/readme_images/F11-Feature-Footer-bar.jpg?raw=true "Partner links")


### F12 Google Maps app functionality preserved on Arklow Trails website
Arklow Trails website has been designed so that standard Google maps features (navigation, pan, zoom, choice of mapping background, local points of interest) are still available to the user.  Google maps background mapping provides rich detail to the user.

![More details of a walk](./assets/readme_images/F12-Feature-Google-Map-integrated-data.jpg?raw=true "More details of a walk")
![Six colour-coded walks on Google Maps background](./assets/readme_images/F07-Feature-Google-Map-direction-finder1?raw=true "Mapped Walks")
![More details of a walk](./assets/readme_images/F05-Feature-Walk-Details-Page.jpg?raw=true "More details of a walk")

### F13 Google Interaction with Arklow Trails-specific My Maps Data
As many potential site users are already familiar with Google map usages, the data created for the Arklow Trails website allows users to utilise it compatibly in the Google Maps interface.   clicking on either a route or its associated start-point (generally indicated by a colour-coded P on the map) triggers two actions:
![Google Map at centre](./assets/readme_images/GM-click-on-a-walk.jpg?raw=true "Using the Central Map as a start point")
![More details of a walk](./assets/readme_images/F13-Feature-Google-Map-direction-finder2.jpg?raw=true "More details of a walk")


### Features in Scope - refer to excel sheet for details of user stories (requirements) features and RTM.
This website includes 5 pages and 13 features 
The pages are:
* Landing Page (image link)
* Walks detail page (image link)
* Gallery page (image link)
* Feedback page (image link)
* About page (image link)

### Landing Page
The landing includes a responsive google map at centre, surrounded by category cards for each of the walks.
This section introduces the user to the geographic territory of arklow and the map is useful to give an overview of the walk locations e.g.  seaside vs  inland.
There is very little text (header bar) displayed initially which means that language barriers are reduced and the site becomes very accessible to visually confident users.

![Landing Page](./assets/readme_images/P01-Landing-Page.jpg?raw=true "Central Google Map with 3 walk flipcards either side")

- __Walk descriptions__
To be completed...

- __Walk reviews__
To be completed...

- __Walk Gallery__
- The gallery will provide the user with supporting images to see what each walk look like.
  - The gallery identifies objects of interest that the user may encounter on each walk.
     - This section is valuable to the user as it encourages them to partake in a given walk. 

- __Feedback form__ 
including ability to upload image of user's own walk

- __Links__
 to partner websites.  Appears in the footer and also on the 'about' page

- __The Footer__ 
  - The footer section includes links to the relevant social media sites (to be completed)...
  - also links to partner sites
  The links will open to a new tab to allow easy navigation for the user. 
  - The footer is valuable to the user as it encourages them to keep connected via social media and to engage in a deeper way with the community sponsors of this project

- __The Feedback Page__
  - This page encourages the user to add their own reviews relating to various walks
  - and to upload their photos
  - and to add a star rating
  - the user must provide a username and email address in order to be permitted to upload photos.  They must also accept the terms and conditions.


![Sign Up](https://github.com/lucyrush/readme-template/blob/master/media/love_running_signup.png)

For some/all of your features, you may choose to reference the specific project files that implement them.
Consider whether a separate utilities file will be used...
To be completed...

### Features Left to Implement
In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

- Another feature idea
Include suitability of various walks for dogs?
Include details to access guided walks and walking/running groups in the area?
Newsletter signup?
Moderation of user feedback - text and photos; and ability to upload this into the site content

### RTM
Requirements traceability matrix showing link between user stories and implemented/ future-release features

## Technologies

### Langugages
HTML (version)
CSS (version)

### Frameworks & Tools
git
github
balsamiq
... to be completed ...

## Testing 
To be completed ...  remember to include a table here which shows user stories/ user requirements and whether each has a pass/fail result (do I need to repeat each test on different device sizes?)
In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

### RTM-proof
Requirements traceability matrix showing link between requirements and features
Provide proofs of successful testing of each user story

### Validator Testing 
- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Manual Testing
To be completed...

### Multi-device Testing
To be completed...

### Multi-browser Testing
To be completed...

### Unfixed Bugs
To be completed... mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Accessibility
To be completed... e.g. using WAVE WebAIM accessibility evaluation tool.
All pages pass with X errors
(comment here on any errors encountered)

## Performance
To be completed...

## Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 


## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site
 [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 

Double check the articles below:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)
References:
https://bulldogjob.com/readme/how-to-write-a-good-readme-for-your-github-project

### Acknowledgements
Acknowledgements including mentor acknowledgement here
