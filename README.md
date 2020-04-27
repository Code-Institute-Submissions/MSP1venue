
# The Bell Jar: Venue Space Website    <img src="/assets/images/the-bell-jar-logo-black.png" height="100px">

This website was built as an educational exercise for Code Institute. The instruction was to build a static front-end only website. The venue location and all other information on the website is fictional.

This website is inspired on my own current job managing a venue location. The website is set up to give information to potential clients about what kind of spaces we have available, the (technical) support and catering facilities and a general sense of the vibe of the venue. It also gives the potential clients information on pricing and allows them to fill out a booking request form which will put them in contact with the venue manager to discuss details for their event.

The website can be viewed here: https://maururo.github.io/MSP1venue/.

## UX ##

The website is designed for the site owner, whose goal is to attract potential clients and inform about our venue spaces and to have them book or get in contact with the venue. The type of consumer relationship is both Business to Consumer as well as Business to Business. However, the type of product is a “one-off” product of relatively low impact to the functioning of the client business, therefor it is not to be expected that the standard informational setup for B2B is required, though detailed information will be provided in links to PDF sheets (technical equipment and catering menu). Also the details of the sale and all that’s included will be discussed and finalized in ensuing correspondation with the venue manager.
Here is a list of User Stories:
* As I user I want to book a venue for a lecture.
* As a user I want to get an impression of the available spaces.
* As a user I want to check if the venue meets the technical requirements for my event.
* As a user I want to look at the catering options for my event.
* As a user I want to get an idea of the price range for the venue spaces.
* As a user I want to contact the venue.

The original wireframe for the basic design idea can be found here: https://github.com/MauRuRo/MSP1venue/blob/master/documents/The%20Bell%20Jar%20WireFrame.pdf
.


## Features ##

### Existing Features ###

* The header – Allows users to identify the brand by the large depicted logo (which is enforced by the “active” design for the current page in the navigation bar) and also allows the user to navigate through the website by using the menu navigation bar. (Every page)
* The footer – Allows users to quickly look up basic contact and social link information. (Every page)
* The (footer) book-button – Allows users to immediately contact the venue for a possible booking, by clicking the button and filling out a modal form. (Every page)
* The Home page – Allows users to immediately get a sense of the kind of venue that this is by having a large image and a simple and powerful slogan.
* The Venue page – Allows users to get a quick overview of the available spaces, their characteristics and the offered equipment and services through two foto galleries, and textual information (enhanced in part by icons).
* The Catering page – Allows users to get a sense of the kind of catering the venue can offer and gives them acces to a menu as well as contact information for the café. The menu is a pdf document that is accesed by pressing a button.
* The Prices page – Allows users to see a comprehensive basic overview of the pricing for the venue spaces through tabular data that is plainly presented.
* The Contact page – Allows users to be reminded of the possibility to get in contact/book the venue by having header text do so with a link in the text as well as a booking button next to the text (equal to the one in the footer). The page also shows the user contact information and opening hours information, as well as a Google Maps view of the location.

### Features Left to Implement ###

* A modal popup post-submission – A nice modal popup that ensures the user their submission has been properly received and that they will be contacted soon.
* An availability calendar – A calendar that shows the user when either of the venue spaces is still available for booking and when it’s already been booked.
* An expanded form with more detailed questions about the proposed event and it's requirements. 

## Technologies Used ##
* HTML5
  * To give the website content and structure.
* CSS3
  * To design the look and layout of the website.
* JavaScript
  * To enable a collapsing navigation menu.
  * To enable a popup message after form submission
* Bootstrap
  * To layout the pages using the Grid system, enabling easy responsive design.
  * To implement a collapsible menu for phone screen viewing.
  * To enable bootstrap button design.
* Cloudfare Hover.css
  * To enable button animation no hover over.
* FontAwesome
  * To enable icons.
* GoogleFonts
  * To set the main fonts for the website.

_Stylesheet and script plugins used:_
* https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css
* https://maxcdn.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css
* https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.13.0/css/all.min.css
* https://cdnjs.cloudflare.com/ajax/libs/hover.css/2.3.1/css/hover-min.css

* https://code.jquery.com/jquery-3.4.1.slim.min.js
* https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js
* https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js

_An additional piece of JavaScript code was used to enable a popup notifation after form submission. This piece of code was found in a fellow student’s project (https://aleesang.github.io/milestone-project-one/?) who made a reference to this website:_
* https://www.w3schools.com/js/js_popup.asp


## Testing ##

SECTION TO BE ADDED

## Deployment ##

This website was deployed using Github Pages and is now accesible here: https://maururo.github.io/MSP1venue/

The first bug I noticed after deployment was that the circular images on the website (catering page and prices page) were not being loaded/displayed on the deployed website.
This turned out to be a source link issue; in development the url "/assets/images/image.jpg" worked fine. However in the deployed website it needed to be "assets/images/image.jpg" (so "/" removed from start).

## Credits ##
### Content ##
* All text content and were made up by myself.
### Media ###
* The photos used in this site were obtained from www.crea.nl (where I currently work) for the venue spaces. For the café manager I obtained a photo from unsplash.com: https://unsplash.com/photos/jOKB3tlCbjc. 
### Acknowledgements ###
I received inspiration for this project from the various Code Institute exercises in the first set of modules: The Whiskey Drop exercise project in particular. I also looked at a fellow students project when I was having some issues: https://aleesang.github.io/milestone-project-one/?.

