# Workout World
This website is created for the new gym Workout World in the center of Stockholm in Sweden. The project is fictional and created for educational purpose.

## UX 
In this section is the explanation of how the website is planed to make it useful, usable and valuble for both the user and site owner using the five planes of user experience. 
### 1 Strategy
The objective of this website is to inform about the gym and its offer to new and existing members. 
The target audience for the gym is people living in Stockholm whom wants to workout at a modern and friendly gym. 
The user on the website is always going to be an anonymous user since it is not possible to log in to the website yet. 
Users goal: wants to know more about the gym and what it offers.
Site owners goal: to create an online presence of the gym and to inform about what the gym offers. 

#### User stories 
* As a user, I want to know what type of memberships the gym offers. 
* As a user, I want to know what a membership cost.
* As a user, I want to find out how to contact the gym. 
* As a user, I what to see what classes the gym offers. 
* As a user, I want to find out when the classes are available. 
* As a user, I what to know what opening hour the gym has. 
* As a user, I what to know where the gym is located. 

### 2 Scope 
The focus of the is for new and excisting members to easily find information abot the gym, its offer and how to get in contect with the personel at the gym. 
Since it is a b2c website it is important to have easy digestable content on the site and this has been taken into consideration when building the site, 
to have big pictues and small sections with text to make it easier for the user. 
### 3 Structure 
For the structure of the page is designed with a linear narrative to make the site easy to use from the first time visiting it.
The navigation bar is placed at the top of the browser window and is sticky so that it is easy to go where you want on the website.
On the landingpage of the site more genreal information and an offer is representet and then you can move on to more detaild information on the other sides of the webpage. 
### 4 Skeleton
Wireframes where developed for the website to ensure that the content is presentent is in line with the strategy and goal of the website and to make sure that the arragement amongst the emelments work. 
Visual methaphors in the form of icons is used in some places to make the content easier to interpret for the user. 
For the structure the more general information and perks of the gym is represented because this content is proritised to get users interested. When you continue on the navbar 
to the right more detail information is presented for those who are interested and furtherst to the right in the navbar the contact page is placed. 

Balsamiq was used to create wireframe for the website, the wierframes are linked below. 
* [Desktop](/assets/wireframes/desktop-wireframes.pdf) 
* [Tablet](/assets/wireframes/tablet-wireframes.pdf) 
* [Mobile](/assets/wireframes/phone-wireframes.pdf) 

### 5 Surface

#### Color

The color scheme used for this project is to create a minimalistic and modern design with high contrast between the lighter turquoise and the darker colors. 
![Color scheme](/assets/images/color-scheme.jpeg)

#### Typography 
The fonts used in this project is both found on google fonts, Montserrat is used for the headings paired with the font Lato for bodytext which was a popular pairing according to google fonts.
The fallback font for both headings and bodytext is Sans-Seriff. 

## Features 

### Existing Features
- Navbar
    - The navbar will be sticky so that the user always can easily can get to different parts of the webpage 
    and become a dropdown menu on tablet and phone. 
- Footer 
    - The footer will contain links to social media so the user can easily fin the gym on social media 
    and a link to the contact page so that it is always easy for the user to find out how they can contact the gym.
- Home
    - Navbar (described under navbar)
    - The homepage will have a heroimage underneath the navbar with an offer on it to get the users attention. 
    - Underneath the heroimage on the homepage some of the benefits with the gym will be presented 
    to emeidietly let the user knows some of the advantages of the gym. 
    - Footer (described under footer).
- Membership
    - Navbar (described under navbar). 
    - On the membership page the three different memberships will be presented so that the user know what memberships are avalibe and their prices. 
    - Underneath the memberships on the membership page there will be a picture where the student discound is presented 
    so that the users that are students know they can get a discount on the memberships.
    - Footer (described under footer).
- Class schedule
    - Navbar (described under navbar).
    - On the Class schedule page underneath the navbar there will be a heroimage with the main heading on it. 
    - Underneath the heroimage on the class schedule page the schedule for the classes will be so the user can se when the classes take place. 
    - Underneath the schedule for the classes the instructors will be shortly presented so that the user can get to know the different instructurs a little. 
    - Footer (described under footer).
    
- Contact
    - Navbar (described under navbar).
    - On the contactpage under the navbar the different ways to contact the gym will be presented so that the user know the different ways they can contact the gym. 
    - Underneath the diffrent ways to contact the gym there will be a contact form if the user wants to fill that out instead of using some of the other ways to contact the gym. 
      This form will reload the page.  
    - Footer (described under footer).

### Features Left to Implement
* A way to sign up to become a member on the website.
* Link pictures from the gym's instagram on the website. 
* A google maps to see where the gym is located.

## Technologies Used
* [HTML5](https://en.wikipedia.org/wiki/HTML5) used as the main programming language. 
* [CSS](https://en.wikipedia.org/wiki/CSS) used to add style to the project. 
* [Bootstrap](https://getbootstrap.com/) used to style some elements and to make the website responsive. 
* [Fontawesome](https://fontawesome.com/) used for the icons. 
* [Google Fonts](https://fonts.google.com/) used to import the two fonts that I used in the project, Montserrat and Latol. 
* [Gitpod](https://www.gitpod.io/) used to develop the project.  
* [Github](https://github.com/) used to hoast the project. 
* [Balsamiq](https://balsamiq.com/) used to create the wireframes. 
* [TinyJPG](https://tinyjpg.com/) used to compress the images. 
* [Photoshop](https://www.adobe.com/se/products/photoshop.html?sdid=8JD95K3Z&mv=search&ef_id=eca789e041d41a016e7ae9d20a38c22d:G:s&s_kwcid=AL!3085!10!79577224923347!79577349402192&msclkid=eca789e041d41a016e7ae9d20a38c22d) was used to edit some of the images. 

## Testing

### Validation 
* To test the HTML I used the [W3C Markup validation Service.](https://validator.w3.org/)
At first the was a warning message because I had put the logo as a H1.
I made some research, and it seems that the best is to not use the logo as a h1 especially since 
I have a logo at the bottom and the top pf every page and you should only use one h1 per page. 
After i changed this there eas no errors or warning to show. 
* To test the CSS I used the [W3D CSS Validation Service.]https://jigsaw.w3.org/css-validator/
There were no errors in the CSS-code and the code vas validated at CSS level 3 + SVG. 

### User stories testing 
- As a user, I want to know what type of memberships the gym offers.
    - At the memberships page the user can see the three different memberships that the gym offers under Our memberships. 
- As a user, I want to know what a membership cost.
    - At the memberships page the user can see under Our Memberships what the prices of the different memberships is and the sign-up fee. On the same page there is also underneath the memberships information about student discount so that the users that are students can know that the gym offers 15% student discount on all memberships. On the home page you can also see that new members can try out the gym for one week free of charge. 
- As a user, I want to find out how to contact the gym.
    - On the contact page the user can find all the ways they can contact the gym, on phone, email, on sight and via a contact form. The opening outs for the reception is also stated if you want to call or talk to someone on sight. In the footer there are also links to the gyms social media if the user wants to connect with the gym there. You can also find a link to the contact page in the footer. 
- As a user, I what to see what classes the gym offers.
    - On the class schedule page the user can find a schedule of the classes the gym offers in the schedule. 
- As a user, I want to find out when the classes are available.
    - On the class schedule page the user can also find out when the different classes are held in the schedule. 
- As a user, I what to know what opening hour the gym has.
    - On the home page you can se under the Why Workout World? That the gym always is open and under the contact page you can see the opening hours of the reception. 
- As a user, I what to know where the gym is located.
    - Under the contact page you can see the address to the gym under Contact and on sight.  

### Responsiveness
The responsiveness was tested using Chrome and Mozilla Firefox DevTools. 

The responsiveness is tested on these devices with Chrome DevTools: 
*	Moto 4
*	Galaxy S5
*	Pixel 2
*	Pixel 2 XL
*	iPhone 5/SE
*	iPhone 6/7/8
*	iPhone 6/7/8 Plus 
*	iPhone X
*	iPad 
*	iPad Pro 
*	Surface Duo
*	Galaxy Fold 

The responsiveness is tested on these devices with Mozilla Firefox DevTools: 
*	Galaxy S9/S9+
*	iPad
*	iPhone 6/7/8
*	iPhone 6/7/8 Plus 
*	iPhone X/XS
*	Kindle Fire HDX

Changes done to make the webpage responsive on all devices tested: 
*	I changed the schedule from having its breakpoint to col-xl from col-lg because otherwise on iPad Pro Sunday in the schedule dropped down below 
the other days of the week and stretched the whole width of the screen. 
*	I changed the padding of the social media icons in the footer because other wide they didn’t fit on the same line on the iPad and Galaxy Fold. 
*	I put in a media query for the logo on screen sizes with a wax width of 320px to make the logo smaller because otherwise the logo and navigation
 menu didn’t fit on the same line and dropped down below the logo instead. 

### Browsers 
The webpage is tested on Google Chrome, Mozilla Firefox, Microsoft Edge, Safiari and Internet explorer. 

### Performace with lighthouse
To test the performance of the project I used Lighthouse.
The first times that I used lighthouse the performace of the pages wasn't that good, to fix this I compressed the images that I used 
because the filesizes was pretty big, I also squared the images used for the instructors in Photoshop to make the performance better. 
The SEO is also omproved by adding a metadescription to all the pages. 

The Lighthouse scores are first presented for desktop for each page and the second one is for mobile. 
#### Home page
![Lighthouse desktop home](/assets/images/desktop-home.JPG)
![Lighthouse mobile home](/assets/images/mobile-home.JPG)
#### Memberships page 
![Lighthouse desktop memberships](/assets/images/desktop-memberships.JPG)
![Lighthouse mobile memberships](/assets/images/mobile-memberships.JPG)
#### Class Schedule page 
![Lighthouse desktop schedule](/assets/images/desktop-schedule.JPG)
![Lighthouse mobile schedule](/assets/images/mobile-schedule.JPG)
#### Contact page 
![Lighthouse desktop contact](/assets/images/desktop-contact.JPG)
![Lighthouse mobile contact](/assets/images/mobile-contact.JPG)
### Manual testing
1. Navbar 
    * Clicking the logo reloads the home page.
    * Clicking the home link reloads the home page.
    * Clicking the memberships link brings user to the membership page. 
    * Clicking the class schedule link brings user to the class schedule page. 
    * Clicking the contact link brings user to the contact page.
    * Hovering over the links to make sure they become lighter when hovering over them. 
    * Scrolling dow the page the navbar stays at the top of the browser window. 
    * This was repeated on all pages to make sure the navbar works on every page. 

2. Footer 
    * Clicking the logo reloads the home page. 
    * Clicking the Facebook icon brings user to facebook.com in a new browser window. 
    * Clicking the Instagram icon brings user to instagram.com in a new browser window. 
    * Clicking the Linkedin icon brings user to linkedin.com in a new browser window.
    * Clicking he contact link brings user to the contact page.
    * This is repeated on all pages to make sure the footer works on every page. 

3. Contact form 
    * Go to the contact page 
    * Trying to submit the form emty and an error message appears to fill out required fields. 
    * Trying to submit the form without a valid email adress and a error message appears. 
    * Trying to submit the form with all the required information and the page reloads. 

### Bugs 
#### Fixed buges
* It's a gap on the screen to the right on mobile verision for everything but the navbarthat disepears after pressing something on Moto G4, Glaxy S5 pixel 2, pixel 2 XL Iphon 5/SE, iphone 6/7/8, iPhone X, Galaxy Fold, Surface duo in Chrome DevTools.
  After googling this problem i started to check that i didn't have any element that was exceeding more than 100% of the screen width. I could'n fint any so I inserted overflow-x: hidden for html and body
  in my css file that i found in [this](https://stackoverflow.com/questions/46012482/unwanted-white-space-on-right-side-in-mobile-view/46012924) thread on Stack Overflow that fixed the problem. 
* Images don't work when deploying the website on github. Fixed this by changing the image filepaths from absolute to relative instead.

#### Open bugs
* Hero images on Class Schedule page and home page and the student discount picture get a bit squashed on internet explorer. 
 
## Deployment
### Deploy 
1. Log in to your github account. 
2. Find the desired repository and click on it.
3. In the toolbar click on Settings. 
4. Scroll down until you get to GitHub Pages. 
5. Select the branch master and click save. 
6. The link is now avalible under GitHub Pages in the high-lighted green area. 
7. When clicking on the link you will access the website. 
### Run code locally
1. Find the repository and click on it.
2. Above all the files click on code next to the green gitpod button.  
3. Here you can choose to clone the repository or to download a zip-file that you can unpack and deply in a local environment.

## Credits 

### Code 
Most of the code in this project was written by me, however some of the code I got from other that are presented below. 
* The navbar is taken from bootstrap and costomized to fit my project. 
* Bootstrap is used to make the content responsive and to style some elements. 
* In my css file I used a piece of code found in [this](https://stackoverflow.com/questions/46012482/unwanted-white-space-on-right-side-in-mobile-view/46012924) thred on Stack Overflow to fix a layout problem on smaller screensizes, this is described in more detail in the bugs section. 
* I used a pice of code from [this](https://www.youtube.com/watch?v=O7WbVj5apxU&t=583s) youtube video made by Dev Ed to set the background on some items on the website, there are comment in the code in the regarding places. 

### Media 
* Hero image on home page by [Li Sun](https://www.pexels.com/@823sl) from [pexels](https://www.pexels.com/) 
* Student discount picture on memberships page by [Ivan Samkov](https://www.pexels.com/@ivan-samkov) from [pexels](https://www.pexels.com/) 
* Hero image on class schedule page by [Victor Freitas](https://www.pexels.com/@victorfreitas) from [pexels](https://www.pexels.com/) 
* Picture of the instructor Anna on class schedule page by [Leah Kelley](https://www.pexels.com/@leah-kelley-50725) from [pexels](https://www.pexels.com/)
* Picture of the instructor Kalle on class schedule page by [Elle Hughes](https://www.pexels.com/@elletakesphotos) from [pexels](https://www.pexels.com/)
* Picture of the instructor Philip on class schedule page by [Laker](https://www.pexels.com/@laker) from [pexels](https://www.pexels.com/)