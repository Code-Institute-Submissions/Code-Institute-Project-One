# Website planning

## Strategy
**What am I creating?**

A website to allow people to sign up for a cybernetic implant service.

**What do we do?**

Sell and install cybernetic implants. Inform people about the cutting edge technology.

**What do we want?**

An operational website. Ease of use, it should be intuitive and easy to navigate. Priority on getting sign ups.

**What does a user want when visiting a website for cybernetic implants?**

* sign up immediately
* browse/view the available products easily
* find out detailed information and technical specifications about the products
* option to contact us with further questions

#### User stories

* As a customer, I would like to be able to sign up easily so that I can save time browsing
* As a customer, I would like to be able to view all available products in a concise format so that I can save time browsing
* As a customer, I would like detailed information about the products so that I can make an informed decision
* As a customer, I would like to be able to contact someone with any questions I have about the product so that I have all the information I require


## Scope

### Webpages

* home/index
* sign-up (maybe modal window)
* products
* product info
* about us
* contact


**home/index**

* nav bar
* bg image, header/welcome message type thing (inspired by whiskey drop module)
* footer

**products**

* nav bar
* implants listed
* footer

**product information**

* nav bar
* detailed product info/technical specs
* footer

**about us**

* nav bar
* company information
* information about what cybernetic implants are.
* footer

**contact**

* nav bar
* short sentence. contact form
* footer

### Functional Requirements

* The site will be public and available to anyone
* Users are able to sign up for the service
* Navigation around the whole site
* A contact form

### Content Requirements

* Home page with sign up button and welcome message
* List of available implants with detailed information on a separate page
* Information about the company, what we do and what we are offering
* Contact information


## Structure

### Interaction Design

* Following convention on navigation - mobile on bottom, desktop on top
* Logo links to home
* Additional contact on footer and social links at the bottom
* Home page information gets the user interested and has a call to action
* Similar colour theme and content layout on all pages

### Information Architechture

* Mostly tree structure
* Potential for dashboard style on products page

## Skeleton

### Navigation Design

* Mobile navigation at bottom with burger icon
* Navigation bar at top for desktop
* Navigation arranged in order of importance to business objectives

### Interface design

* CTA button on home page
* Cards listing products with links to further information (maybe modal)
* Contact form for additional questions

### Surface

* Sans-serif fonts, consistent families across the site
* Limited set of colors to create a consistent theme. Contrasting colors to emphasize things such as sign up button.
* Dark/black theme with white text and bright colors to attract attention to content
* Large background image on home page with phrase and CTA
* Consistent background/foreground theme across site. Not sure if same image on every page or similar color but different.



--------------------------

<!-- To do -->

- reorganise css
    classes > element targetting (instead of new classes)
    new sheet for seperate pages - main,
    look into compiler
    *create common style classes like 'skin' - https://www.smashingmagazine.com/2011/12/an-introduction-to-object-oriented-css-oocss/
    reusable classes of common styles

- Decide on background for other pages and then figure out footer layout
- Remove scrolling on mobile home page
- Make sure all fonts are styled correctly
- Figure out how I want about page content aligned on desktop (once I've written the actual content)
- Set Rubik global font family at top of css - remove all from classes, leave orbitron in classes
- Double check footer positioning is same on all pages and sizes
- change all hex to 6 digit, change white text to off white hex or rgba for nav links
- don't forget modal styling



<!-- extra stuff -->
- add tapering borders to mobile nav
- map link to address
- products dropdown menu for desktop
- b2b enquiries contact us
