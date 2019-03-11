# User Centric Front End Milestone Project

Welcome to my Front End Milestone Project. My website is made for the alternative rock band The Pixies. 
It is made to exhibit their music and videos, announce news and tour dates and be a point of contact for fans to sign up to their newsletter. 

## UX
This website will be used by fans and/or potential fans interested in listening to the Pixies music and keeping up to date with the band's tour dates and latest news announcements. 
It will also give fans an opportunity to sign up to an email newsletter as well as display contact information about the band's booking agents/managers.

  * As a fan/potential fan, I want to learn about the latest band-related news such as announcements of new music and tour dates.  
  * As a fan/potential fan, I want to be able to listen to the band's new music and have access to their back catalogue.  
  * As a fan/potential fan, I want to to be able to watch music videos featuring the band including production videos and videos of their latest live performances. I also want to see photos from their instagram feeds and latest shows.  
  * As a fan/potential fan, I want to check their latest tour dates and would like to have the ability to buy tickets to those shows.   
  * As a promoter/booker, I want to know how to contact the band's management in order to potentially book them for events.  

## Wireframes
My project began with the wireframes in the links below but the design of the pages developed as I made them. I added the parallax scrolling banner image on every page after I made the wireframes as it made the top of the page where the user sees first more impressive. 
On the mobile wireframe design, I have the main Logo at the top of the page but eventually decided to hide it on mobile view as it wasn't necessary with the mini-logo in the top left hand corner. 
Another change I made from the wireframes was to split the 'Media' page in to two pages; 'Listen' and 'Watch'. The 'Media' page would've been too big and visually confusing so I changed the 'Listen' page so it only displayed audio content and the 'Watch' page to video and photos of the band. 
I have added a wireframe of the 'Watch' page but the audio page is still labelled 'Media'.
The last change I made that deviated from my wireframes was to the Footer. I removed the music app links and added them to the Audio page and I added the email sign-up form and a 'Back-to-Top' button. 

  * [Mobile Wireframes](https://github.com/johnnycistudent/Pixies-Front-End-Project/blob/master/assets/documents/mobile_wireframe.pdf)
  * [Desktop Wireframes](https://github.com/johnnycistudent/Pixies-Front-End-Project/blob/master/assets/documents/desktop_wireframe.pdf)


## Features

### Existing Features
#### Nav Bar
The Navigation Bar features a small image of 'The Pixies' logo in the top left with a link back to index.html. The menu for the website with each page is featured on the right of the Nav bar which collapses into a burger icon when in mobile view. Each page font is in grey and transitions to white when hovered over.

#### Parallax Banner Hero Image
Each page features a Hero Banner Image under the Nav Bar that make up the second part of the header. The Banner Image is an image of the band either performing live or from a photoshoot that provide a different visual experience for each page. The parallax effect makes the banner image move at a different speed than the rest of the website when scrolling. The Parallax effect is disabled in mobile and tablet views. 
The 'Pixies' logo features underneath the Nav Bar and on top of the Banner Image and contains a link to the index.html. The Logo disappears on mobile view to avoid overcrowding the screen for users as the smaller logo in the navbar is enough to display the band's brand.

#### Footer Email Sign-Up
The Footer on each page features a form from Bootstrap's documentation that allows users to sign up to Pixies newsletter email for updates and news about the band and includes a data-based disclaimer about using the user's info. 

#### Footer Social Media links
The Footer features six Social Media links to the Pixies' various social media and music streaming accounts: Facebook, Twitter, Google Plus, Instagram, Spotify and Youtube. The buttons are based on a Bootsnip.com code that I customised to suit the website. 
Each social media button is represented by a FontAwesome icon in white. When hovered over by the user, each icon expands and scales up and changes colour to the recognised color of the social media brand. The links open a new tab in the same browser window when clicked on.

#### Home Page
The home page features a customised Jumbotron from Bootstrap's documentation underneath the Banner image advertising the band's latest album and a large "Listen" button in red underneath that stands out in contrast to the grey background. The home page also features the latest news updates with links to the "Listen" and "Tour" pages of the website as well as external links to the featured stories that open in a new tab when clicked. 

#### 'Listen' Page
The 'Listen' page features the audio content of the website. Each Pixies full studio album is embedded on this page from Spotify. The user can listen to 30 second clips of the songs from the embedded player if not signed in to Spotify or can visit Spotify from a link in the player.  In mobile view, the embedded albums display one per row but expand to two per row in medium view and then to three per row in desktop view. Each embedded album features buttons directly below them that link to various popular downloading and streaming sites where the user can purchase, download or stream the album.
Below the embedded albums are a more extensive list of links of where to download/purchase the band's music featured in larger buttons.

#### 'Watch' Page
The 'Watch' page features the visual content of the website, namely Video and Photos. The videos follow a similar formula to the embedded albums on the 'Listen' page, where the embedded videos have buttons below linking externally to puchasing/video streaming sites. The videos featured are a combination of live performances, official music videos and fan-made vidoes. 
Below the videos section is the Photos section where there is a photo carousel from bootstrap's documentation displaying photos of the band from recent gigs and photoshoots. 

#### 'Tour' Page
The 'Tour' page exhibits the band's tour dates and gives the user the opportunity to book tickets. The tour dates are displayed in a table from Bootstrap and each date is punctuated with a red "BOOK" button. 

#### 'Contact' Page
The contact page gives users/promoters the chance to get in touch with the band's management in order to book them for live shows. The page features the band's management contact details and also features a contact form for general queries. The form is from Bootstrap.   

## Technologies Used
* [HTML](https://www.w3schools.com/html/html5_intro.asp) - [CSS](https://www.w3schools.com/css/) - [Javascript](https://www.w3schools.com/js/)

    This website is written mainly using HTML and CSS and to a lesser extent javascript.

* [Cloud9](https://c9.io/login)

    This website was written on Cloud9. 

* [Bootstrap](http://getbootstrap.com/docs/3.3/css/)

    This website uses Bootstrap 3.3.7 for its framework. 

* [JQuery](https://jquery.com/)

    This website uses JQuery which helps implement javascript features from Bootstrap. 

* [FontAwesome](https://fontawesome.com/)

    This website uses icons from FontAwesome mainly for social media icons but also used to help illustrate in the headings.

* [Google Fonts](https://fonts.google.com/specimen/Roboto+Mono)

    This website uses 'Roboto Mono' as it's main font with two different weights from Google Fonts. 

* [GitHub](https://github.com)

    This website's repository is hosted and published on GitHub. 

## Testing

### Testing User Stories

#### 1. User Story 1 - As a fan/potential fan, I want to learn about the latest band-related news such as announcements of new music and tour dates.
 
#####   Test 1: View latest news 

   **i.** Go to the Home/Index Page.   
   **ii.** Scroll down to the "Latest News" section.   
   **iii.** Click on one of the news stories, photos or "Read more" links that opens the original article in a new tab.   
   **iv.** Click on one of the other links associated with the stories to book tickets to shows or go to the music player.   

#####   Test 2: Sign up to the band's mailing list

   **i.** Scroll down to the footer on any of the pages and locate the mailing list sign up form.   
   **ii.** Verify that an error message appears when an empty field is submitted.   
   **iii.** Verify that an error message appears when no email address is present.   

#### 2. User Story 2 - As a fan/potential fan, I want to be able to listen to the band's new music and have access to their back catalogue.
  
#####  Test: Listen to audio tracks
  
   **i.**  Click on the "Listen" tab in the header.   
   **ii.** Navigate to one of the Pixies albums on the page.   
   **iii.** Click on the play button on the album to play 30 second snippets of each song.  
   **iv.** Click on the links below each album for more download options or navigate to below all the albums for even more downloading/streaming options.   

#### 3. User Story 3 - As a fan/potential fan, I want to to be able to watch music videos featuring the band including production videos and videos of their latest live performances. I also want to see photos from their instagram feeds and latest shows.

##### Test: Watch video content

   **i.**  Click on the "Watch" tab in the header.   
   **ii.** Scroll down to the videos. Play, pause, full screen and adjust volume on embedded players.   

#### 4. User Story 4 - As a fan/potential fan, I want to check their latest tour dates and would like to have the ability to buy tickets to those shows. 
 
##### Test: View tour dates and book tickets.
 
   **i.** Click on the "Tour" tab in the header or access from one of the links in the "Latest News" section on the index page.    
   **ii.** Scroll through the tour dates and click on one of the "Book" buttons to verify it takes you to a site that enables you to book tickets for that venue.   

#### 5. User Story 5 - As a promoter/booker, I want to know how to contact the band's management in order to potentially book them for events.
  
##### Test: Enquire about booking the band  
  
   **i.** Navigate to the "Contact" page by clicking on the tab in the header.   
   **ii.** Enter your name, email and query into the respective fields.  
   **iii.** Verify the form will not allow you to submit without all the fields correctly filled out and that the email address field is valid.    
   
### Responsiveness  

I have tested out the responsivesness of the website on Google Chrome and Mozilla Firefox using Dev tools. I have also tested the website on the devices below, both in horizontal and vertical view ports and they have all worked nicely.
   
  * Small devices - iPhone 6s, Samsung J5, Samsung S9. 
  * Medium devices - iPad. 
  * Large/Extra Large devices - Lenovo ideapad 520, Asus Vivobook.  

### Validation

I have validated my html code through [https://validator.w3.org/](https://validator.w3.org/) and my css code through [http://jigsaw.w3.org/css-validator/](http://jigsaw.w3.org/css-validator/) and no errors have occurred.

## Deployment
The code for this website was pushed from Cloud9 to a repository in GitHub and is published on GitHub where you can access it here:

[https://johnnycistudent.github.io/Pixies-Front-End-Project/](https://johnnycistudent.github.io/Pixies-Front-End-Project/)

## Credits
This website was designed by John O'Connor. 

### Content

  * The text on the homepage for the three news stories were written by myself summarising the below articles.
    [https://www.stereoboard.com/pixies-tickets](https://www.stereoboard.com/pixies-tickets)
    
    [https://www.billboard.com/articles/columns/rock/8483866/pixies-surfer-rosa-puerto-rico-frank-black](https://www.billboard.com/articles/columns/rock/8483866/pixies-surfer-rosa-puerto-rico-frank-black)
    
    [https://www.rollingstone.com/music/music-news/pixies-announce-massive-30th-anniversary-surfer-rosa-reissue-705482/](https://www.rollingstone.com/music/music-news/pixies-announce-massive-30th-anniversary-surfer-rosa-reissue-705482/)

  * The Tour dates on the 'Tour' page and the contact info on the 'Contact' page are from the Pixies official website:
    [http://www.pixiesmusic.com/shows/](http://www.pixiesmusic.com/shows/)

### Media 

  * The Logo and mini-logo were obtained from:
    
    [Logo](https://upload.wikimedia.org/wikipedia/en/8/85/The_Pixies_logo.png)
    
    [Mini Logo](https://turnupthatvolume.files.wordpress.com/2017/08/pixieslogo2.jpg)

  * The images from the 'Home' page were obtained from:

    [Hero Banner Image](https://valleyadvocate.com/wp-content/uploads/2017/09/Pixies_0607_BW_hi-copy-1.jpg)
    
    [Jumbotron album cover Image](https://media.npr.org/assets/img/2016/09/19/pixiesalbumart_sq-72bf6151e164be8afc76308152a25e96c771d2fd-s800-c85.jpg)
    
    [1st story](http://www.fueledbyramen.com/sites/g/files/g2000005606/f/201810/Weezer_Pixies_Instagram_Story_wDates_1080x1920_Static.jpg)
    
    [2nd story](https://www.billboard.com/files/styles/article_main_image/public/media/pixies-1989-billboard-1548.jpg)
    
    [3rd story](https://www.rollingstone.com/wp-content/uploads/2018/08/ComeOnPil_SurferRosa-Standard-Vinyl_lo_sm.jpg?w=300)
    
  * The images from the 'Listen' page were obtained from:
    
    [Hero Banner Image](http://larecord.com/larwp/wp-content/gallery/dec2017_pixies_hollywood-palladium/Pixies-2.jpg)
    
    [All audio files on this page are embedded from Spotify](https://open.spotify.com/artist/6zvul52xwTWzilBZl6BUbT)
    
    [Apple music button image](https://www.chasingcoral.com/wp-content/uploads/2017/09/listen-on-apple-music-badge.png)
    
    [Spotify music button image](https://medicalschoolhq.net/wp-content/uploads/2018/02/listen-on-spotify-1024x359.png)
    
    [Amazon music button image](https://static1.squarespace.com/static/5a627e7c80bd5e4208582014/5bec508a1ae6cf66cda73e6c/5bec508a03ce640e332ed396/1542213913213/amazon-music.png)
    
    [Youtube music button image](https://static1.squarespace.com/static/59605e61b8a79bc707f41adb/t/598b10eae6f2e199ff0f7640/1534711077881/)
    
    [Google play music button image](https://upload.wikimedia.org/wikipedia/commons/thumb/c/cd/Get_it_on_Google_play.svg/1280px-Get_it_on_Google_play.svg.png)
    
    [Deezer music button image](https://static1.squarespace.com/static/59d0aed3e45a7c855f6fe993/59df68e664b05fcb66e7a6ba/59e094bfe3df287c5804cf86/1507892908064/deezer.png)

  * The images from the 'Watch' page were obtained from:
    
    [Hero Banner Image](https://scontent-dub4-1.xx.fbcdn.net/v/t1.0-9/16114093_10154889973922442_7036852731440663618_n.jpg?_nc_cat=103&_nc_ht=scontent-dub4-1.xx&oh=e13490c4ad141e4e1409bf4e0b13afcc&oe=5C8E0BB3)
    
    [All video files are embedded from Youtube](https://www.youtube.com/channel/UCEMVQmE2DNpGqdwJi7-o5LQ)
    
    [1st Photo carousel photo](https://scontent-dub4-1.xx.fbcdn.net/v/t1.0-9/46323420_10156793731212442_1051819288718999552_n.jpg?_nc_cat=102&_nc_ht=scontent-dub4-1.xx&oh=59af81518de138aa475873234d62f3e2&oe=5CA6D439)
    
    [2nd Photo carousel photo](https://scontent-dub4-1.xx.fbcdn.net/v/t1.0-9/14079629_10154436063712442_533863648643693801_n.png?_nc_cat=111&_nc_ht=scontent-dub4-1.xx&oh=06a2c6f63c768bb803d67b7c035e176a&oe=5CA80D22)
    
    [3rd Photo carousel photo](https://scontent-dub4-1.xx.fbcdn.net/v/t1.0-9/45216611_10156759059137442_8192266713979420672_n.jpg?_nc_cat=106&_nc_ht=scontent-dub4-1.xx&oh=909b089c58c4ed212b4873a23d9f3ea4&oe=5C8D5994)
    
    [4th Photo carousel photo](https://pbs.twimg.com/media/Dr2xiZcU0AAIuVu.jpg)

  * The images from the 'Tour' page were obtained from:
    
    [Hero Banner Image](https://scontent-dub4-1.xx.fbcdn.net/v/t1.0-9/28795569_10156170690237442_4808262423842652160_n.jpg?_nc_cat=104&_nc_ht=scontent-dub4-1.xx&oh=3b720f87a83c65e48b713667d8d1d827&oe=5CD286EE)

  * The images from the 'Contact' page were obtained from:
    
    [Hero Banner Image](https://scontent-dub4-1.xx.fbcdn.net/v/t1.0-9/35927089_10156441710987442_5343484291739287552_n.jpg?_nc_cat=108&_nc_ht=scontent-dub4-1.xx&oh=427a042485a1f9d706cc4668301f1612&oe=5C8C15EE)

## Acknowledgements
  * I consulted [Stack Overflow](https://stackoverflow.com/), [W3Schools](https://www.w3schools.com/) and [Slack](https://slack.com/) during the making of this project for general queries. Slack was especially useful for seeing what other people thought of the design of the website.   
  * I used a lot of documentation from [Bootstrap v3.3.7](http://getbootstrap.com/docs/3.3/css/) which is credited in the comments in the html. The social media icons in the footer were taken from this [Bootsnip code](https://bootsnipp.com/snippets/84kpo) and edited to suit the website.
  * I would also like to thank my mentor Rick for his guidance during the making of this project.

