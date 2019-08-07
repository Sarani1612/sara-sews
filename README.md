# The Nimble Thimble

My website is for a potential boutique sewing shop that sells custom-made
clothing and costumes.

[Website](https://sarani1612.github.io/the-nimble-thimble/)

## UX

This website is for individuals and smaller theatres looking for somewhere to get custom-made clothing and costumes.
Since the concept and services provided are fairly simple and easy to grasp, I did not think large amounts of text would be desirable or helpful.
Instead I wanted a clean, elegant and simple layout with short statements and a few calls to action, and otherwise let the focus be on the photos of some of the business' previous work.
I decided this approach would be best, given that visitors to the website were more likely to be interested in seeing the business' portfolio rather than spend time reading a lot of text.

### User stories

+ as a first-time user of the site, I can easily move through the different sections without clicking randomly in vain.
+ as an individual interested in having a special item of clothing (wedding dress, gifts, cosplay costumes) custom-made, I can easily determine whether this business caters to me and my needs.
+ as a potential professional client without much time to do thorough research, I can quickly look through the business portfolio to get an idea whether they are able to deliver what I need.
+ as a potential client, I can quickly locate the About page to get an impression of the people I might be doing business with.
+ As a potential client, I can quickly get in touch with the business for enquiries or to request a quote.
+ As a potential client, I have easy access to the business' social media accounts where I can most likely get more information and see more photos.


### Wireframes

See the wireframes for the website by clicking on the links below. Each file contains the wireframes for the Home, Gallery, Contact and About pages in that order.
1. [Mobile](/wireframes/desktop/mp1-desktop.jpeg)
2. [Tablet](/wireframes/tablet/mp1-tablet.jpg)
3. [Desktop](/wireframes/desktop/mp1-desktop.jpeg)

## Features
The website consists of four pages: Home, Gallery, Contact and About.\
All four pages share the same navigation bar at the top of the page with the name of the business in the left-hand side and links to each page.
They also have the same footer with copyright info and links to three social media pages (Instagram, Facebook and Pinterest).

### Home
The first section of the home page consists of an elegant background photo, the name of the business and a short sub-heading that sums up what kind of business this is.
This section equals the size of the viewport to avoid information overload and prevent the site from having a too busy appearance.\
The user can scroll down to the second section which consists of a short paragraph describing the services provided and a carousel with three photos from the business portfolio.
There are also two calls-to-action; one in the form of a button that will take the user to the Gallery page and another one that will take the user to the Contact page.

### Gallery
The focus of this page are the photos showing off some of the business' previous work. As such, there is only a short text at the top encouraging the user to let their imagination wander while looking through the gallery.\
Underneath the photos there is a call-to-action button linking to the contact page.

### Contact
The contact page consists of a background photo (the same as on the home page) and two main sections. The first section contains address, phone number and email address for the business. in order for it to be more visually pleasing, there are icons depicting the contact info type.\
The section section is a contact form the user can use to get in touch. There are input fields for name, phone number, email and message and these are followed by a submit button.\

### About
The about page is very similar to the contact page in that it features the same background image and two main sections. Here the first section contains a photo of the founder of the business in her sewing studio while the second section
is a text about her and her business. This is the only place where a longer block of text is featured. This was deemed necessary in order to be able to give the user a better impression of the business and the people behind it.\
People are more likely to do business with someone they know a bit more about.

### Existing features
+ **Colour scheme**: a colour scheme has been chosen to tie all the sub-pages and content together. Thus, the navigation bar and footer always have the same dark purple colour while text and icons are held in white.\
For consistency, the buttons are held in the same colours; dark purple bakcground with white text.\
For sections without a background image, i.e. the *Projects* section on the *home* page and the *gallery*, a lighter purple has been chosen as the background colour as the dark purple would have taken too much attention away from the content.\
Text throughout the site (apart from in the navbar and footer) has the same dark purple colour as the navbar and footer.
+ **Animations**: for a visually pleasing user experience, AOS animations have been added to most of the sections and photos throughout the site.
+ **Navigation bar**: all four pages have a navigation bar at the top of page with links to the pages, so that the user can easily navigate between them and not have to use the back and forward buttons in the browser.\
The bar is fixed to the top so that it is always visible even when scrolling down. This prevents the user from having to scroll to the top when they want to go to another page.
+ **Footer**: there is also a footer on all four pages. It contains copyright info and links to social media so that the user can find additional information by visiting the business' accounts on these sites.
+ **Carousel**: the *home* page contains a carousel with three portfolio photos, that are meant to show some of the business' previous work and make the user want to see more.
+ **Calls-to-action**: throughout the site there are several call-to-action buttons which have been strategically placed. For example on the *gallery* page where there is a contact button immediately after all the portfolio photos.
In addition, immediately after the carousel on the *home* page there is a button linking to the *gallery* page and another linking to the *contact* page. The same two call-to-action buttons are placed on the *about* page immediately after the text.\
On the other hand, the *contact* page only contains one call-to-action button, i.e. the button for submitting the contact form. Placing links here would be risky given that they could potentially lure the user away from making contact with the business.

### Features left to implement
The following features are some that could be implemented later on for a better user experience:
+ **Videos**: some catwalk style videos could be added to the Gallery to better show off the business' previous project.\
Clips from plays that the business has provided costumes for could be useful to potential business clients.
+ **Testimonials**: adding a couple of testimonials from previous and/or current costumers would help the business image and make them appear more trustworthy and competent.
+ **Detailed About page**: Photos/videos of the sewing studio and the staff along with individual bios for each member of the staff could also help enhance their image and trustworthiness.
+ **Gallery enhancement**: the file-size of the photos has been reduced for faster loading, but there is still some room for improvement here. Good results could likely be achieved with [lazy loading images](https://imagekit.io/blog/lazy-loading-images-complete-guide/).\
In addition, it would be good if the user was able to click each photo to open a larger version and then be able to click through the photos using back and forward arrows.

## Technologies used
I used the following technologies in making my website:

+ HTML and CSS were used for the overall structure of the website.
+ [Bootstrap](https://getbootstrap.com/): used to help make a visually appealing layout responsive to different screen sizes.
+ [Google Fonts](https://fonts.google.com/): provided the font used throughout the website.
+ [AOS Animate on Scroll](https://michalsnik.github.io/aos/): used to add animations to the sections and photos on the website.
+ JQuery: used for Bootstrap and AOS.

## Testing
The HTML code for all four pages was put through the [HTML Validator](https://validator.w3.org/) to check for errors.\
The CSS code was put through the [CSS Validator](https://jigsaw.w3.org/css-validator/) to check for errors.

### Testing user stories
1. as a first-time user of the site, I can easily move through the different sections without clicking randomly in vain.
    - 
2. as an individual interested in having a special item of clothing (wedding dress, gifts, cosplay costumes) custom-made, I can easily determine whether this business caters to me and my needs.
3. as a potential professional client without much time to do thorough research, I can quickly look through the business portfolio to get an idea whether they are able to deliver what I need.
4. as a potential client, I can quickly locate the About page to get an impression of the people I might be doing business with.
5. As a potential client, I can quickly get in touch with the business for enquiries or to request a quote.
6. As a potential client, I have easy access to the business' social media accounts where I can most likely get more information and see more photos.

### Manually testing all content and features across website

## Deployment
I set up a new environment in AWS Cloud9 where I did all of the coding for the website.
I also created a new public repository on GitHub to which I pushed the Cloud9 repository from the command line.\
To deploy the website I went to the settings tab for the depository on GitHub and set the master branch as the publishing source and a few moments later the website was available on GitHub Pages through the link provided at the top.

### Running the project locally
Follow these steps if you wish to run the project locally:
1. go to the [repository page](https://github.com/Sarani1612/the-nimble-thimble) on GitHub
2. click the "clone or download" button on the right-hand side
3. copy the URL that shows up
4. in Terminal, change the current working directory to the location where you want the cloned directory to be made
5. type 'git clone' and paste the URL from step 2
6. press enter
7. the local clone will be created

These instructions are taken from [this GitHub help page](https://help.github.com/en/articles/cloning-a-repository)

## Credits

### Content
+ The texts used throughout the website were written by Sara Larsen and Robert McGuinness.

### Media
+ All photos used are free stock photos from [Pexels](https://www.pexels.com/).
+ All the icons on the website are from [Font Awesome](https://fontawesome.com/).