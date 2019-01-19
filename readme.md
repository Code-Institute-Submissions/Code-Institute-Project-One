# Zenith Technologies | Code Institute Milestone Project One

Build a frontend only website to demonstrate understanding of the User Centric Frontend Development module of the Code Institute course. I have chosen to build my own idea for a fictional company in the future that provides cybernetic implants for humans.

--------------------

## Design Planning

I have a separate planning document which goes into the different planes of UX and how I used them to design this website. I came across the concept of agile development and I liked it, so I have also documented changes to the initial design that came about through different iterations. This can be found [here.](planning/planning.md)

I used the program Pencil to design wireframes for both mobile and desktop, which can be found [here.](planning/wireframes)

### To summarize

* This is a website for people to sign up for the business' service providing cybernetic implants.
* The business wants a functional website that is easy to use to allow for sign up's and providing necessary information.
* The user wants to be able to sign up with minimal time spent, learn more about the products and the business, and be able to contact someone with any questions.

### User Stories

* As a customer, I would like to be able to sign up easily so that I can save time browsing.
* As a customer, I would like to be able to view all available products in a concise format so that I can save time browsing.
* As a customer, I would like detailed information about the products so that I can make an informed decision.
* As a customer, I would like to be able to contact someone with any questions I have about the product so that I have all the information I require.

### Website Layout

* Five content pages and a sign up modal.
* Different navigation for mobile and desktop.

### Website Styling

* I decided to use a dark/black main theme as I liked this for the nature of the content. I designed a logo which has some nice colours that stand out on the black. I chose a particular blue from this logo as the primary colour and used an opposite colour tool to choose a dark but vibrant orange as the secondary colour.
* Product and background images are mostly dark/grey, with a nice contrast between the background and the content.
* I chose two fonts. The main font used on all navbars and larger text areas is simple to read and in white or light grey. The second font is used only for the home page headers and sign up button and has matches the type of product the business is dealing in.

--------------------

## Features

* Sign up button - allows users to register for the business' service by having them fill out a sign up form.
* Expanding product information - allows users to view both a simple product overview and more detailed product information by clicking on the product.
* Contact form - allows users to contact the business by having them fill out a contact form.
* Different navigation for mobile and desktop to allow easier use depending on the platform.

--------------------

## Technologies Used

* [Bootstrap](https://getbootstrap.com)
    * used for ease of creation of functional components and website layout.
* [Google Fonts](https://fonts.google.com)
    * a good selection of fonts.
* [Font Awesome icons](https://fontawesome.com/)
    * used for social media icons.
* [JQuery](https://jquery.com)
    * required for Bootstrap functionality.
* [Popper.JS](https://popper.js.org/)
    * required for Bootstrap functionality.

## Resources

* [https://hackerthemes.com/bootstrap-cheatsheet](https://hackerthemes.com/bootstrap-cheatsheet)
    * Speeds up development
* [https://stackoverflow.com](https://stackoverflow.com)
* [https://www.quora.com](https://www.quora.com)
* [https://developer.mozilla.org/en-US/](https://developer.mozilla.org/en-US/)
* [https://tinypng.com/](https://tinypng.com/)
* A lot of google!

--------------------

## Testing

* The website was constantly tested during development using Chrome dev tools. I used this to resize the browser to check new code was working, breakpoints, and different mobile/tablet screen sizes. I also used it for live editing to build the site.
* Tested load times on my mobile device using mobile data.
* Tested sign up and contact form with and without inputs in all fields.
* Tested all links on all pages.

--------------------

## Deployment

* Deployed using Github Pages - [https://asdfractal.github.io/Code-Institute-Project-One/](https://asdfractal.github.io/Code-Institute-Project-One/)
* Tested everything listed above again once deployed.
* I tested the website on all my personal devices (Desktop computer, Macbook Pro, iPad, LG G6 phone, Oukitel 10000 phone.) I checked in both portrait and landscape and tested the responsive design, navigation, links, modals and form submission.
* Additionally tested using -
    * [Google Mobile Friendly Test](https://search.google.com/test/mobile-friendly) and received a mobile friendly result for all pages.
    * [Webpagetest](https://www.webpagetest.org/) - [(result)](https://www.webpagetest.org/result/190113_X7_beb233f33919742b9638bd8b0adebdd5/) and received a satisfactory result.
    * Dev tools audit and after resolving the issues listed below received a result between 98-100 on all categories.

## Issues encountered

* Upon testing on webpagetest I discovered a 404 error on favicon so I googled what this is and implemented an icon.
* It was suggested I use gzip compression but after doing some research on this I believe it is beyond the scope of this project for me to implement.
* Received a low grade on caching, again did research on this and I believe it is also beyond the scope of this project.
* Testing on my iPad in landscape I encountered an issue with size due to the address bar showing, which I didn't anticipate since devtools doesn't show it.
* Testing on my Macbook Pro I realised that the resolution height is quite a bit smaller than my desktop and some elements were not looking correct.
* Testing on Dev Tools audit I realised the contact form didn't have aria labels and that I had a duplicate id on the contact form and modal signup form.
* I showed the website to one colleague at work and when I saw him look at it he didn't seem to notice the mobile navmenu at the bottom of the page. Upon showing another friend and having my mentor session I got similar feedback.

#### Steps taken to resolve issues

* Made some minor adjustments to padding for tablet media query.
* Researched common desktop screen size and added a media query for screen height to separate them.
* Added aria labels to contact form and fixed duplicate id name.
* I did some more research on mobile navigation and found that my original information about nav at the bottom was primarily about apps with a bottom navbar and not the burger menu on websites. Decided to change the mobile nav to be on the top right of the page to be more consistant with current web standards.


--------------------

## Credits

### Image sources

* Logo image by Geralt on pixabay
* [Home and product background](https://wallimpex.com/)
* [About background](https://invardin.com/robot-1650649_1920/)
* FAQ background by Kate Rowe on Unsplash
* Contact background by Tony Webster on Unsplash
* Products
    * [Nexus](https://www.flickr.com/photos/sanjayaprime/4924462993)
    * Matrix by Geralt on pixabay
    * [Aegis](https://commons.wikimedia.org/wiki/File:Cybersecurity.png)
    * [Neuroptimal](https://www.flickr.com/photos/alansimpsonme/34752491090)
    * [Core](https://www.kisspng.com/png-top500-computer-science-electronic-circuit-king-ab-1144035/)

### Acknowledgements

Landing page inspired by Code Institute 'Whiskey Drop' lesson

--------------------

*Website for educational purposes only*
