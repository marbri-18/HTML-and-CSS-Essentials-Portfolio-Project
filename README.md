# HTML-and-CSS-Essentials-Portfolio-Project
Portfolio project for Code Institute course: Diploma in Software Development (E-commerce Applications)

---

# TINTOON

## Description
The Tintoon website promotes a fictional Tintop App which is a spoof version of the Tinder dating app. On Tintoon the human target audience is replaced by popular cartoon characters. The purpose of the web-site is to sell the Tintoon application to potential users so they are encouraged to Download the Tintoon App, Subscribe for a pricing plan or failing that register their details so they can be informed of future promotions and marketing information.

The Tintoon website consists of three pages. The Homepage (index.html) is a landing page with a header/banner section, a features section, a price plan section and a download section. The Gallery page (gallery.html) displays a collage of testimonials of previous satisfied customers in the form of figures. The sign Up page (sign_up.html) includes a form for users to register their details and in doing so be subscribed to receive special custom offers.

The Tintoon web-site is based on a walkthrough project I completed in 2021 for a Udemy course I was learning on. The Course was called 2021 Web Development Bootcamp and was facilitated by Angela Yu of the App Brewery. The original walkthrough project was called Tindog and was similarly based on the Tinder App. The Tindog project was a single landing page with four sections. It was a project for learning the use of Bootstrap. At the time of completing the project, I exchanged the Dog dating theme for a Cartoon Character dating theme. For completing the HTML and CSS Essentials Portfolio Project 1, I thought it would be a valuable learning outcome for me to recreate the Tintoon website while not relying on Bootstrap but to create the visual appearance using only CSS. I have also extended the site to three pages including a Gallery and Sign Up page. The digital illustrations of well known Warner Brothers cartoon characters were all created and formatted for use on the website by myself using Affinity Designer. 

### Screenshots

#### Homepage (index.html)
![Screenshot demonstration of homepage responsivity.](https://github.com/marbri-18/HTML-and-CSS-Essentials-Portfolio-Project/blob/main/assets/images/Homepage_responsive.png)

  #### Gallery Page (gallery.html)
  ![Screenshot demonstration of gallery page responsivity.](https://github.com/marbri-18/HTML-and-CSS-Essentials-Portfolio-Project/blob/main/assets/images/gallery_responsive.png)
  
  #### Sign Up page (sign_up.html</h4>
  ![Screenshot demonstration of sign-up page responsivity.](https://github.com/marbri-18/HTML-and-CSS-Essentials-Portfolio-Project/blob/main/assets/images/Signup_responsive.png)
  
  ### Features
  
  #### Navigation Bar
  ![Screenshot of navigation bar.](https://github.com/marbri-18/HTML-and-CSS-Essentials-Portfolio-Project/blob/main/assets/images/navbar.png)
  The Navigation bar includes the brand title of the website - Tintoon - which links to the homepage. There are further links aligned to the right to the Home Page again, the Gallery page and the Sign Up page. As the screen width is reduced the links aligned right are replaced by a hamburger icon, When clicked on the hamburger menu expands to display a dropdown menu of the three right aligned links and the hamburger icon. Clicking on the hamburger icon again rolls the dropdown menu back up. The Tintoon brand logo displays at all screen widths. The Navigation bar displays across the full width of all three of the website pages.
  
  #### Footer
  The footer displays the copyright info for the website. links to the Bolshie Pig website (The website creators presonal website). A contact E mail link and social media links via the social media logo icons. The footer displays across the full width of the screen on all three website pages.
  
  ### Homepage 
  
  #### Banner header section
  
  ![screenshot of banner/heading section on homepage](https://github.com/marbri-18/HTML-and-CSS-Essentials-Portfolio-Project/blob/main/assets/images/banner_heading_section.png)
    
   the banner heading section displays the heading which alerts the user to what they can get from the Tintoon app. This is enclosed on either side by two images of cartoon       characters portraying in love poses. The user is given an immediate opportunity to download the app since this is the major objective of the site. This section is styled using CSS flexbox. As screen width is reduced the articles change from left right alignment to top bottom alignment.
      
  #### Features section
  ![Screenshot of features section on homepage](https://github.com/marbri-18/HTML-and-CSS-Essentials-Portfolio-Project/blob/main/assets/images/feature_section.png)
   
   The features section informs the user of three key reasons why they should use the Tintoon app. This section also utilizes the flexbox CSS styling to ensure it is responsive to screen width.
  
  #### Pricing plans section
  ![Screenshot of pricing plans section on homepage.](https://github.com/marbri-18/HTML-and-CSS-Essentials-Portfolio-Project/blob/main/assets/images/pricing_section.png)
 
 The pricing plan section tells the user of the range of plans and prices and what each plan delivers. This section also utilizes the flexbox CSS styling to ensure it is responsive to screen width.
  
  #### Download section
  ![Screenshot of download section on the homepage](https://github.com/marbri-18/HTML-and-CSS-Essentials-Portfolio-Project/blob/main/assets/images/download_section.png)
  
  The download section offers the user another opportunity to download the Tintoon app before leaving the homepage.
  
  ### Gallery Page
  ![Screenshot of gallery page.](https://github.com/marbri-18/HTML-and-CSS-Essentials-Portfolio-Project/blob/main/assets/images/gallery_page.png)
  
  The gallery page displays figures with testimonials attached to them from former satisfied fictional cartoon characters. The page conveys to the cartoon user that celebrity characters have used the site before and have glowing comments to make. At full screen width the figures are set up in four columns but as the screen width is decreased the columns accordingly decrease to three, two and a single column. This has been done by using media queries set at relevant breakpoints to decrease the column count incrementally.
  
 ### Sign-Up page
 ![Screenshot of sign-up page.](https://github.com/marbri-18/HTML-and-CSS-Essentials-Portfolio-Project/blob/main/assets/images/signup_page.png)
 
 The sign-up page represents a final opportunity to maintain engagement with a potential App user. If the users interest has not been sufficiently arroused for them to download the App and sign up for a plan, this page allows users to register their details so they might recieve customised pricing plan offers. The sign up page has two articles. One article aligned to the left contains a poster style section advising the user to sign up for the special offers. The right hand article is the form for users to submit their details. Media queries with relavant CSS drive the responsiveness for this page. 
  
  ### Validation  
  The Tintoon website has been passed through the W3Schools html validator. There are no outstanding errors. There are 9 warnings on the homepage, 1 warning on the gallery page and 2 warnings on the sign-up page. All these warnings relate to an absence of h1 to h6 headers at the beginning of sections or articles. In all instances this is due to an alternative approach being used - eg the use of icons in the homepage features section or internal divs or sections within sections
  
  The Tintoon website has been passed through the W3Schools Jigsaw CSS validator. No errors were reported.
  
  The Tintoon website was passed through the Google Chrome Developer Tools lighthouse extension. The following screenshot image shows the results from the report.
  
  ![screenshot of Google Developer Tools Lighthouse report.](https://github.com/marbri-18/HTML-and-CSS-Essentials-Portfolio-Project/blob/main/assets/images/Lighthouse.png) 
   
  ### Bugs
  A bug occured in the functioning of the navigation bar and the displaying of the hamburger icon when the screen width was reduced. This was resolved by setting the CSS display property to block. Subsequently another bug emerged relating to the display of the drop down menu. This had been caused by the space before the `responsive` class in the script file being deleted. Re-instating the space resolved the problem.
    
  ### Unfixed bugs
  There are no known oustanding bugs.  
    
  ### Deployment
  The Tintoon website has been deployed on [Github](https://marbri-18.github.io/HTML-and-CSS-Essentials-Portfolio-Project/)
  All files used in the Tintoon website can be viewed in my Github repository [marbri-18/HTML-and-CSS-essentials-Portfolio-project](https://github.com/marbri-18/HTML-and-CSS-Essentials-Portfolio-Project)
  
  ### Credits
  
  #### Content
  
  The Tintoon website was based upon a walktrough project from the Udemy course "2021 Web Development Bootcamp" by Angela Yu of the [App Brewery](https://www.appbrewery.co/). The Original project was a landing page site called Tindog. I developed the Tintoon theme while completing the project. The completed version of the Web development bootcamp project can be seen at my personal [website] (www.twodeadwombles.co.uk)
  
  I learnt how to create the responsive top navigation bar with a hamburger icon and used code from [W3 Schools](https://www.w3schools.com/howto/howto_js_topnav_responsive.asp)
  
  I uesd W3 Schools as a learning resource for flexboxes used on the homepage
  
  Icons used in the Tintoon website were downloaded from [Fontawesome](https://fontawesome.com/)
  
  #### Help and Support
  I recieved valuable advice help and support from my code Institute assigned mentor Sammy Dartnall. I had three hour long mentoring sessions during August/September 2021. The last session was on Thursday 23 September.
  
  The Tintoon website was completed following the completion of the Code Institute HTML and CSS Essentials module. The first module of the Code Institute's Diploma in Software Development (E-Commerce applications).
  
  #### Media
  I used [Balsamiq](https://balsamiq.com/) to produce wireframes for project planning. The wireframes have been uploaded to my [HTML and CSS essentials project portfolio repository](https://github.com/marbri-18/HTML-and-CSS-Essentials-Portfolio-Project/blob/main/Tintoon_%20Portfolio%20Project%201.pdf)
  
  I used codeply to explore many of the CSS layouts before adding them to the project. Examples of my Codeply workouts can be found on my [Codeply page](https://www.codeply.com/u/marbri_18)
  
  I used Affinity designer to create the digital illustrations of cartoon characters for all images used in the Tintoon website. All illustrations are of cartoon characters originally appearing in Warner Brothers, Looney tunes or Hanna Barbera productions.
