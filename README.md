# Project 0

Web Programming with Python and JavaScript

For Project 0, Ive created a personal website detailing some information and interests of mine. The website consists of 4 webpages, a CSS stylesheet, and an SCSS stylesheet. Every webpage also utilizes bootstrap, and the grid feature is active in every page, which was how I implemented the sidebar.

index.html is the code for the homepage of my website. The page uses bootstrap to create the sidebar (this is done in the other pages as well.) The page contains some basic information of me, as well as nested unordered and ordered lists detailing my interests. The page also contains hyperlinks to the other three pages on the website.

page1.html is the code for a page describing my high school. The page contains a link to my school's homepage, as well as hyperlinks in the sidebar to the other pages in the website. The page also contains an image of campus, as well as bootstrap buttons. When pressed, the buttons have an activation event which changes the url of the image element, therefore allowing the picture to be changed using the buttons.

page2.html is the code for page describing my music tastes. The page contains a link to my favorite artists' spotify page, as well as a styled table detailing my 5 favorite songs, and links to their spotify pages.

page3.html simply contains some more information about my hobbies. The page is linked to a SCSS stylesheet as well as a regular stylesheet. 

general.css is the main stylesheet for my website. The stylesheet uses many CSS properties, including color, width, font-size, font-family, and background-color. The page also uses more than 5 selectors; for example: .class, #id, a general selector, a descendent selector, and a , selector. The style sheet also inludes a @media query to reduce font size on smaller windows. However, the bootstrap stylings tended to mess with my desired stylings, so I tagged the majority of my text under a div with the id #bootstrapOverridetext, which was then defined in my stylesheet, because specific id definitions have more priority than the class definitions in bootstrap. 

The styles.scss and its compiled version contain specific scss stylings for page3.html. They include the variable $mainColor, which styles text color of subordinate lists, as well as nested selection for lists, and finally, a overarching template for text, which is then inherited by the lists.