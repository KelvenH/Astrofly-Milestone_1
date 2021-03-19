# Astro:Fly - Milestone Project 1



## Links to;

[Astro:Fly - Live Site](https://kelvenh.github.io/Astro-Fly_Milestone_1/index.html)

[GitHub Repo](https://github.com/KelvenH/Astro-Fly_Milestone_1/)

[Wireframes - v.Balsamiq](README-docs/Wireframe-Astrofly-Full-v.Balsamiq.bmpr)

[Wireframes - v.PDF](README-docs/Wireframe-Astrofly-Full.pdf)

***

## Contents

1. [Overview](#Overview)
2. [UX;](#UX)

   [- User Stories](#User-Stories)
   
   [- Personal Goals](#Personal-Goals)
   
   [- Scope](#Scope)
   
   [- Structure](#Structure)
   
   [- Skeleton](#Skeleton)
   
   [- Surface](#Surface)
   
3. [Content & Design Features](#Content-and-Design-Features)
4. [Styles](#Styles)
5. [Technologies Used](#Technologies-Used)
6. [Testing](#Testing)
7. [Bugs and Defects](#Bugs-and-Defects)
8. [Deployment](#Deployment)
9. [Acknowledgements](#Acknowledgements)



---
## Overview
Astro:Fly is a fictional company offering space tourism / commercial flights. In this scenario, the service has recently launched some routes with additional offerings to come and a web site is being launched to garner public interest, provide information and register details of potential clientele. This project has been undertaken for educational purposes to demonstrate HTML and CSS essential skills (Code Institute Milestone Project 1). Any referrences to technologies are purely fictional and are not based on scientific fact.  

---

## UX

### User Stories 
(Fictional Scenarios)

#### Business Requirements 
Astro:Fly require a site which;
- generates buzz and excitement to the general public and media
- conveys image of a safe and ethical brand (despite the slight irony the service could have on planet earth / airspace)
- provides prospective clients with summary of planned voyages tus leading to the registration of potential clientele

#### Client Goals 
Site visitors are expected to fall into 1 of 3 categories;
- media; the new service is expected to create attention due to this being an extreme niche service / limited rivals
- general public; seeking latest information on the planned service such as timelines, what services will be offered and images 
- prospective clients, who are; 
      - able to find information about the services provided
      - clear and easy navigation through the site
      - easy registration of personal details for more information / booking.  

### Personal Goals 
(Actual)
Through this project I am looking to; 
- Demonstrate understanding and application of HTML and CSS essential skills.
- Broaden personal awareness of further capabilities of HTML and CSS which go beyond those covered in module 1.
- Experience challenges, bugs, errors and frustrations through which problem solving will be a huge value-add / personal learn.
- Understand the limit of my current capabilities - looking to stretch myself without trying to achieve the impossible for a coding noob! 
- Serve as an example for a future portfolio of web site design and development which will also be used as an entry point which future projects can be assessed against to demonstrate improvements.
- The subject chosen for this project is to be fun, engaging but also on an area where broad range of dramatic / exaggerated design elements can be employed and have relevance - as opposed to a more traditional retail site where these would be out of place (e.g. use of transitional effects, fonts, color palette).
- Be proud of the final output!

### Scope 
(what's on the table for inclusion?)
  - landing / home page - welcome, intro and enticement to remain on site
  - detail of services - what, where, how?
  - gallery - images
  - client registration (modal form)
  
### Structure
(how is information structured and logically grouped?)
  - consistent theme across sites
  - header / navigation menu and footer mirrored across all pages
  - central / main content to remain same theme / branding but adapted to suit requirements of that page and be interesting / exciting to the users.
  - content over minimu of 3 pages to include Home, Sales and Gallery

![SitePlan](README-docs/Wireframe-SitePlan.png)

### Skeleton 
(how information will be presented / navigated)
 - all pages must be responsive 
 - navigation will primarily be through the menu (to appear as drop down on small screen devices and potentially permanent sidebar for larger screens)
 - additional links added to act as shortcuts 
 - outine available in Balsamiq - example shown below
 
 ![InitialConcepts](README-docs/Wireframe-InitialConcepts.png)
 ![MidLevelDesign](README-docs/Wireframe-Mid-Level-Design.png)
 ![HigherSpecMock-up](README-docs/Wireframe-HigherSpecMock-up.png)

### Surface
(what will the finished product look like; color palette, fonts, images and other design elements)
  - initial outline developed in Balsamiq with extracts shown above)
  - mock-up of final rendering (screen grabs)

![Screenshots](README-docs/Screenshots.png)

---
## Content and Key Design Features

Page | Features | In Build | Comments |
-----|----------|----------|----------|
General | Navigation menu and footer to social media links| Yes | 
Home | Intro, Countdown timer to next launch, news ticker | Yes | Majority of features included although some 'workarounds' e.g. countdown timer only counts down for a speciic time and resets on page load.
Flights|Oerview of the services provided with embedded images| Yes | Scaled back initial plans due to overall volume and some design elements which would have relied upon JS|
Sign-Up|Modal Form to register for details| Yes | in addiiton to sale enquiries page was also used to highlight and register for membership|
Gallery |animated scroll through of images|No - animation requires JS|Opted to embed images within Flights page|
404 Error Page|Mock 404 page to be linked to for inactive links in Navigation | No | Page built with auto-forward to index page but removed on advice of mentor not to have redundant links.

---
## Styles

### Site Theme

Considered | Selected| Notes|
-----------|---------|------|
Cyberpunk | No | Whilst preferred to style selected, expect this would require additional resources, time to incorporate which would detract from primary objectives for the project
Vintage (e.g. 70's prediction of future) | No | For same reasons as given above.
Futuristic | Yes | Expect these to be more easily available and achieved through basic shapes / easily available images |

Extract of Balsamiq design elements - initial considerations;

![Mood Board](README-docs/Mood_Board.png)


### Color palette 

Opted for smart, sophisticated visual branding with futuristic styling. Image below displays colors used. These are partially shown against a dark background to indicate transparency levels.

![Color Palette](README-docs/Color-Palette.png)


### Fonts and Typography
In keeping with the futuristc theme, the basic text uses font types sourced from GoogleFonts.

![Font-Baumans](README-docs/FONT-Baumans.png)

Another GooleFont was used for a slight difference appearance where looking to imply digital display
![Font-Orbitron](README-docs/FONT-Orbitron.png)


A more dramatic font was sourced for the company logo and H1 headings.
('Ethnocentric' licence purchased for usage via fontspring.com)

![Font-Ethnocentric](README-docs/FONT-ethnocentric.png)

![Font-Ethnocentric](README-docs/FONT-Ethnocentric-2.png)

Special fonts were used for particular purposes; the digital countdown clock and digital news ticker. 
(Digital & LED fonts available on free license for non-commercial use via dafont.com)

![FONT-digital-7.png](README-docs/FONT-digital-7.png)

![FONT-AdvancedDotDigital7](README-docs/FONT-AdvancedDotDigital7.png)

### Responsive Font Groups

Font types, colors and sizes were added to the Root Directory (see style.css for details). Additionaly, i took this one stage further by creating responsive font groupings. Each grouping comprises of a font family, font size, color and in some cases varaition on font weight. 'Clamp' was also applied to the font size to set min / max size and retain better control through responsive resizings. Example shown below. This enabled consistent application across content.
Note, these are shown on single lines (as opposed to standard line by line property) as found this easier to refer to. 

![Responsive-Font-Groups](README-docs/Responsive-Font-Groups.png)

### Special note on SVGs - intention was to provide a sci-fi themed User Interface. Inspiration was from combination of Sci-Fi films / tv, PC games and search on Sci Fi / Concept User Interfaces via Pinterest. Specific sites useful for research;
https://sciencefictioninterfaces.tumblr.com/
https://www.saji8k.com/kit-fui/movie/
Initially, time was invested in understanding clip-paths to style the element borders. However, upon imlementing challenges arose due to responsive and dynamic re-sizing of elements resulting in squashed / stretched elements. 
In researching how these could be over-come, I learnt about SVGs and the benefits of these for responsiveness. Time was then spent on constructing some very effective SVGs and whilst these were more flexible, they also suffered due to the dynamic sizing. For example, the content of drop-down tabs differs, which again impacted the display of the SVG (i.e. strecthed / overflow for longer content and empty spacing for shorter content). Thorough research was conducted to try and retain these artefacts. A basic understanding of SVGs properties specifically ViewBox, sizng and 'retainAspectRatio'. 
I then discovered the 'border-image' property. The challenges here was that i wanted to use an axiting 'frame' (SVG) whereas this property seemed to be more appropriate for using images as repeating patterns. Initially i thought the border-slice property would enable me to accomplish the task. But although i could define which parts of the SVG should be used for which part of the border, it still resulted in stretch / collapse of the SVG sides (dynamic content)  and some sideways adjustments for the responsive sizings.
The final route i looked at was to split the SVG into three parts - a top, middle and bottom. Logic here was that as most of the movement was in the height, if i kept the styling to the top and bottom sections changes in the height (which would only be straight sections) would not be compromised - especially when i discovered properties on the individual SVG code can instruct not to change the line thickness. After trials, this seemed to be workabe - but then i encountered challenges with implementing these particularly the CSS behaviour. The top and bottom sections would be considered as empty divs by CSS (if loaded as background-images) which meant applying fixed heights (not responsive) so would need to be coded as images.Whilst the middle panel would have text, the combination of image and background-images were not aligning correctly (and due to the partial transparency overlaps / gaps would be seen. Additionally this resulted in very small top/bottom sections (as no text). Loading all 3 parts as images was also fruitless as to displaying text over the image required it to be positioned absolutely which i was unable to retain alignment for the three parts (typically the bottom panel would extend over the text as this had been taken out of the flow.

Unfortunately the only route which seemed to make these workable, would be to have a whole series of different sized SVGs to select from. Whilst initially looked to proceed it became apparent that this was overly burdensome (both in terms of their construction, allocation and ID tagging) and significant time invested vs. the benefit - which was afterall only cosmetic! 

Therefore, the key text panels are not using SVGs but merely make use of background-color, border and opactity along with 'digital' styled font to create a semi-illusion of being displayed on a glass digital surface. Additional box and text shadows applied with hover and active states to give an impression of being lit.

There has been some useage of SVGs retained. A few small graphics (satellite, dish and globe on home screen - sourced from Adobe Stock) were acceptable as not used to hold text. A few self built SVGs were retained, these can be seen as background panels in the nav bar, and as a HUD style graphic (Home page) which only houses a company logo.  
The self-built SVGs were inspired by examples seen on Adobe Stock and built in Adobe Illustrator. I then exported the code and to try and minimise file size and loading times, ran these through an on-line tool https://jakearchibald.github.io/svgomg/.
I opted to load these as seperate files (as opposed to adding the code into the HTML mark-up) to keep the HTML and CSS sheets manageable!
In some instances, further adjustments were required to get the SVG sizing correct. For these i used an SVG viewbox generator (https://codepen.io/designcourse/live/mdydjBa) which allowed me to visually see the adjustments needed to the viewbox properties to either take part of an SVG file (i.e. dish and satellite were uploaded initially on same file). 

A significant number of on-line articles were referred to, but particulalry useful referrences were;

https://svgontheweb.com/#implementation
https://css-tricks.com/mega-list-svg-information/ (a number of useful articles linked from here)
https://mastery.games/post/dynamic-svg-components/



---
## Technologies Used

Languages:
HTML5
CSS3
(whist Javascript has not been used directly, there are aspects applied through use of Bootstrap)

Bootstrap 4.5
Google Fonts
Font Awesome
Adobe Photoshop
Adobe Illustrator
Blendr


---
## Testing

---

## Bugs and Defects

---

## Deployment

---

### Acknowledgements
- slack community 
- mentor
- Whatsapp group
- Balsamiq introduction tutorials for wireframes
- getbootstrap.com
- csstricks.com
- codepen.io
- w3schools.com
- Github community
- YouTube (Kevin Powell and Dani Krossing) - 
- image sources - Adobe Stock, Shutterstock, Pexels and Depositphotos?

