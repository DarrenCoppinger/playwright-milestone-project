<h1 align="center">
<img src="https://i.ibb.co/0CyqMx5/project-title-image.jpg" alt="Project hero image of Neasa O'Callaghan" width="100%" data-load="full" style="">
</h1>

<h2> 
<a href="https://darrencoppinger.github.io/playwright-milestone-project/">See the website here</a>
</h2>

A website for a contemporary playwright Neasa O’Callaghan”. She is interested in developing a website the satisfies the following criteria:
* Design a website that targets audience members who have seen her work or those who have heard about her from others and wish to see photographs of her productions and read extracts from her currently published or soon to be published works.
* The website must showcase the playwrights work, highlight the identity of the playwright and provide a section were potential collaborators can get in contact with the playwright, such as directors, producers, actors, set/costume designers and other writers. 
* The website should provide links to the playwright's social media platforms which she uses to promote her work. 

This website will portrait a sense of the playwright and her work with a simple but elegant aesthetic. This was achieved through the use of simple clean colors.

The fonts were chosen to give a classic feel, so serif types were used. The fonts were sourced from Google Fonts and are as follows:
* Noto Serif JP
* Parisienne


## UX

### Design Objectives:

* Is the content appropriate for the audience:
The audience for this website will be english speaking theatre goers and artists. The audience is likely a young technology savvy audience and will likely access the site on mobile devices. A mobile first approach was considered appropriate for this type of audience. Although the website will accommodate all visitors its primary audience will be technology literate.

* Is the content relevant?
Yes the content on this site is specific to the playwright (images from productions, and other artistic collaborations, extracts from works). The website makes best use of these assets provided by the playwright. 

* Is the content grouped in an intuitive way?
The content is grouped into easily understood sections (Home, About, Writing, Gallery).

The site also aims to have a simple elegan aesthetic to it to reflect the playwright's sense of style. 

* Is the technology for this content appropriate?

A standard website has been chosen as the method to distribute this information as dedicated platform to supplement her social media presences. Links to her many social media accounts will be provide a central location and ease of access to her updates (plays that she may have seen, projects she is currently working on).

### Business Strategy

* What is the product this website is selling?

The product that we are trying to sell is the works of playwright Neasa O’Callaghan.

* What value are we trying to add to is?

This website adds value to this product by providing a centralised location for potential fans to find the playwright on all social media platforms where she currently promotes her work and the work of her collaborators. The website also provides background information on the identity of the playwright and the factors that inform her work, it will also provide a platform to download extracts from her work. 

* What has been done like this before?
 
The playwright has a social media presence but no current website.
Examples of the websites of other up and come playwrights include:

    * www.Lisa-carroll.co.uk
    * www.vinaypatel.co.uk
    * www.sarahruhlplaywright.com/
    
* What are the technology considerations 

A website is an appropriate technology to reach the widest possible audience. A website will provide a central location to links to the playwright's social media platforms and will provide a repository for sample extracts from the playwright's work.

* Why would a user want this product? What’s worth doing?

Through interviews with the client, interviews with the potential users of this website and reviews of other playwright’s websites a list of development priorities were established. An importance versus viability analysis was also conducted, the results of which are as follows:

<img src="https://i.ibb.co/r4PBy4W/importance-vs-viability-analysis.jpg" alt="importance-vs-viability-analysis" border="0">

The development priorities for this project are as follows:
1.	Provide repository for writing extracts
2.	Showcase writing credits/portfolio 
3.	Create gallery of photos and promotional material of playwright’s productions
4.	Provide central location for all social media links
5.	Provide collaboration section
6.	Provide embedded Instagram feed

### User stories

* Audience Member visits the site 1: I was an audience member at one of the Playwrights productions, I want to find out more about her other work.
* Audience Member visits the site 2: I was an audience member at one of the Playwrights productions, I want to find out more about the playwright.
* Actor/Direct visits site 1: I am an actor/director I hear about Neasa from an audience member, I wanted to find out more about her writing.
* Actor/Direct visits site 2: I am an actor/director I hear about Neasa from an audience member, I wanted to find out more about other productions of her work, particularly images and videos.
* Costumer/set designer visits site: I am an artist or costume/set designer, I hear about Neasa from an audience member, I would like to see images of performances of her work to get a sense of what type of worlds she creates.
* Potential Collaborator visits site: I am an actor/director/artist/costume designer/set designer I want to work with the Playwright and would like to contact her to discuss a potential project.

### Wireframe

* <a href="https://ibb.co/YWC3b32">Home</a>
* <a href="https://ibb.co/gZhMqQ3">About</a>
* <a href="https://ibb.co/d2KKtXb">Writing</a>
* <a href="https://ibb.co/YTpVyD2">Gallery</a>
* <a href="https://ibb.co/44MyrtP">Contact</a>

## Features
### Existing Features
At the top of each page is a stylised version of the client's name and responsive navigation bar at the top of the page. The name also acts as a "Home" button. The "Playwright | Producer" title drops onto the menu bar when the screen size drops to the sm size class

On the footer of each page are social media icons link the the visitor to the client's social media profiles. 
#### Home
The home page has a hero image which is overlaid with a call to action button asking, "Want to work with Neasa?". Clicking this text will bring the visitor to the "Contact" page. 

The hero image is a background images which is held at the top left corner of the image. As the screen size reduces the face of the playwright is kept in frame.

#### About
The about page features a headshot image of the client with a general biography beside the image.
The page includes a timeline of the playwright's theatrical performances, highlight the note achievements of her career.  

#### Writing 
This page includes synopsis of the client's notable work. At the bottom of each synopsis is a button which allows the visit to the site to download extracts from each of the plays.  

### Gallery 
This page consists of rows of thumbnail images divided into 3 sections: images, videos, audio.

The image thumbnails are square with rounded corners. Each image thumbnail can be clicked to launch a FancyBox viewer. The fancy box viewer presents a higher resolution version of the image in its original aspect ratio.  A light shadow appears behind the image which darkens when there are hovered on. There are different numbers of thumbnails on the screen depending on the screen size. There are as follow:
* xs: one thumbnail per row
* sm: two thumbnail per row
* md: three thumbnail per row
* lg: six thumbnail per row

Video are displayed in a 16:9 aspect ratio, the format of the videos themselves. The videos are uploaded to YouTube and embedded on this page using and iframe element.
A light shadow appears behind the video interface which darkens when there are hovered on.
 
The audio section includes an interface for a widget connecting to Spotify where the client has a playlist of songs used for one of the productions she worked on. The widget interface has a light shadow appears behind it which darkens when there are hovered on.

### Contact

This page has a contact form for collecting information on potential collaborators. The form asks for the collabortors name, email address and details of the proposed project. At the bottom of the form is a submit button with the same color and hover affects as the other buttons used on the "Writing" page.

### Features left to Implement
One feature which could be added in a later development sprint is direct feed from the clients Instagram account where she promotes her work and posts high quality publicity imagery. However, this would require java script to implement which is beyond the scope of this assignment. Therefore, it will be implemented at a later time.


## Technologies Used
This project used:
* HTML
* CSS
* <a href="https://fonts.google.com/">Google Fonts</a>
* <a href="https://fancyapps.com/fancybox/3/">FancyBox</a>
* <a href="https://c9.io/">Cloud9</a>
* <a href="https://git-scm.com/">Git</a>
* <a href="https://getbootstrap.com/">BootstrapCDN</a>
* <a href="https://www.youtube.com/">YouTube</a>
* <a href="https://jquery.com/">jQuery</a>
* <a href="https://popper.js.org/">popper.js</a>
* <a href="https://www.responsinator.com/">Responsinator</a>

## Testing
Both of the follow validators were used to check the code developed from this project:
* <a href="https://jigsaw.w3.org/css-validator/">W3C Jigsaw CSS Validator</a>
* <a href="https://validator.w3.org/">WC3 Markup Validator</a>

### User Stories Testing
Audience member visits the site 1: I go her website see I want to see if there are any upcoming performances and see on the front page information on her next play.
1. The audience member sees the home page of the website.
2. They scroll down to the section on "Neasa's Upcoming Work" at the bottom of the webpage and see information on an upcoming performance her new play
3. They follow the link to the theatres webpage in the carousel caption (for md screen sizes and greater) or the text underneath the carousel (for screen size smaller then md) to buy tickets to the next play.

Audience member visits the site 2:
1. The audience member sees the home page of the website.
2. I click the "About" button on the navbar
3. On the about page I find information on the playwright's backgrounds and her past work.

Actor/Director visits site 1:
1. Actor/Director visits site looking to find out more about the playwright's plays. They see the "Writing" button on the navbar and click this button.
2. They are brought to the "Writing" page of the website where they find summaries of two of the client's other works
3. They read the they are interested in one of the plays described so the click on the "Download Extract" buttons underneath the play description.

Actor/Director visits site 2:
1. Actor/Director visits site looking to see images from productions of the playwright's work. They see the "Gallery" button on the navbar and click this button.
2. They are brought to the "Gallery" page of the website where they see three sections of media: images, videos and audio. In the images section they see thumbnails of the images.
3. They see an image/video/audio item they are interested in and click it.
    1. For the images this launches a fancy box image viewer to see the original image
    2. For videos they can play the video embedded in the page/they can make the video full screen/they can click the YouTube button and watch the video on YouTube.
    3. For the audio the song listed on the playlist will begin to play, they click through to the playlist on Spotify by clicking the Spotify icon in the top right-hand corner.

Costumer/set designer visits site:
1. Costumer/set designer visits site wanting to see images from other performances of the playwright's work. They visit the home page of the website and see the "Gallery" button on the navbar and click this button.
2. They are brought to the "Gallery" page of the website where they see three sections of media: images, videos and audio. In the images section they see thumbnails of the images.
3. They click the first image thumbnail; this launches the fancy box viewer.
4. They click through the images from the playwright's performances and publicity material to get a sense of her work and the aesthetic she has created in these past productions.

Potential Collaborator visits site: 
1. An actor/director/artist/costume designer/set designer I want to work with the Playwright. On the "Home" page of the website they see the hero image which has a text box asking, "Want to work with Neasa?"
2. They click this button which brings them to the Contact page.
3. They fill in their name, email address and the details of the project they would like to work with the playwright on.
4. They click the submit button.

### Manual testing of elements and functionality on each page

#### Home

1. Navbar
    1. Visit the Home page on a desktop sized screen (lg)
    2. Hover over the Name Header text "Neasa O'Callaghan" to check that the hover effects work.
    3. Click the Name Header text "Neasa O'Callaghan" to check that it links to the Home page.
    4. Hover over each navbar button to check the hover effect works for each one.
    5. Click on each one of the navbar buttons to ensure that each links to the correct page.
    6. Alter the screen size from desktop size down to mobile (sm) size to check that the navbar is responsive. At that size the navbar changes to the toggler icon and the roles Header "Playwright|Producer" text moves into the navbar to save vertical space.
    7. Click the toggler icon to check that the drop-down menu activates and that the text is centred.
    8. Hover over each of the drop-down menu buttons to make sure the hover effect activates
    9. Click each of the drop-down menu buttons to make sure that they links to the correct page.
2. Hero Image
    1. Visit the Home page on a desktop sized screen (lg)
    2. Alter the screen size from desktop size down to mobile to ensure the clients face is always on screen and that the call to action button is always placed correctly and doesn't obscure the image.
    3. Hover over the call to action button on top of hero image to ensure it reacts
    4. Click the call to action button to ensure that it bring you to the correct page.
3. Carousel
    1. Visit the Home page on a desktop sized screen (lg) and scroll to the carousel in the "Neasa's Upcoming Work" section
    2. Click the forward and back arrows on either side of the slides 
    3. Hover over the highlight "Arcola Theatre" hyperlink to ensure it reacts
    4. Click "Arcola Theatre" hyperlink to ensure it opens a new page and goes to correct website
    5. Alter the screen size from desktop size down to mobile (sm) size, check that the cousel caption will stops being displayed and the description of the image becomes a text box underneath the carousel.
4. Footer
    1. Visit the Home page on a desktop sized screen (lg)
    2. Hover over each of the footer social media buttons to ensure that they react to correctly
    3. Click each of the social media buttons to ensure that they launch the correct social media account in another page
    4. Alter the screen size from desktop size down to mobile (sm) size to check that footer is responsive. At the sm screen size the footer should reform into two rows of two columns.
5. Review of all functionality and responsiveness on mobile screen size by using <a href="https://www.responsinator.com/">Responsinator</a>

#### About
1. Repeat Navbar checks as described in step one of the Home section
2. Hyperlinks
    1. Hover over each hyperlink to check that they each react
    2. Click each hyperlink to make they launch the correct site in another page
3. Resize page down to mobile (sm) size to check that columns are responsive to screen size change and reform into full width rows
4. Repeat footer checks as described in step four of the Home section 
5. Review of all functionality and responsiveness on mobile screen size by using <a href="https://www.responsinator.com/">Responsinator</a>

#### Writing
1. Repeat Navbar checks as described in step one of the Home section
2. Download Extract" Buttons
    1. Hover over "Download Extract" Buttons to ensure they react correctly
    2. Click each "Download Extract" Buttons to ensure it opens the correct pdf document in another page
3. Resize page down to mobile (sm) size to check that columns are responsive to screen size change and reform into full width rows
4. Repeat footer checks as described in step four of the Home section 
5. Review of all functionality and responsiveness on mobile screen size by using <a href="https://www.responsinator.com/">Responsinator</a>

#### Gallery 
1. Repeat Navbar checks as described in step one of the Home section
2. Carousel
    1. Visit Gallery page on a desktop sized screen (lg)
    2. Click the forward and back arrows on either side of the slides 
    3. Hover over the highlight "Arcola Theatre" hyperlink on the Townland image to ensure it reacts
    4. Click "Arcola Theatre" hyperlink to ensure it opens a new page and goes to correct website
    5. Alter the screen size from desktop size down to mobile (sm) size, check that the carousel caption will stops being displayed.
3. Images
    1. Visit Gallery page on a desktop sized screen (lg)
    2. Hover over every thumbnail images to check that the hover shadow animation effect reacts
    3. Check code to ensure that all images have an alt attribute
    4. Click on each thumbnail to check that the FancyBox modal opens for each one and that the correct image is displayed for corresponding to the thumbnail.
    5. In the FancyBox model check that the previous and next button work correctly. Also check that the "Play", "Start Slideshow", "Thumbnail" and close buttons all work correctly.
    6. Reduce the screen size to check that the image reform at the md, sm and xs break points into 3, 2 and 1 col respectively.
4. Videos
    1. Visit Gallery page on a desktop sized screen (lg)
    2. Hover over embedded video to check that the hover shadow animation effect reacts on both videos
    3. Press play button to check each video
    4. Check that the play/pause, volume, settings, YouTube and full screen buttons all work correctly
    5. Reduce the screen size to check that the embedded videos reform at the md breakpoint into full width rows
5. Audio
    1. Hover over the Spotify widget interface to ensure that the hover shadow animation effect reacts
    2. Click the play button to check that the audio files begin to play
    3. Check that the Spotify and Share buttons work correctly
    4. Check that each song on the playlist can be selected
    5. Please note that this feature is only available in preview to those without a Spotify account. This is not considered an issues as presenting audio media is not the primary focus of this site. 
6. Repeat footer checks as described in step four of the Home section 
7. Review of all functionality and responsiveness on mobile screen size by using <a href="https://www.responsinator.com/">Responsinator</a>

#### Contact
1. Repeat Navbar checks as described in step one of the Home section
2. Contact Form
    1. Submit empty form without any data and check that an error message appears in the first empty field
    2. Submit the form with an empty Name field and check that a relevant error message appears
    3. Submit the form with an invalid email address and check that an error messages appears when you do so
    4. Submit the form with an empty project description field and check that an error messages appears when you do so
    5. Hover over "Send Project Details" button to ensure is reacts
3. Resize page down to check that the form is responsive to the change in width and never goes beyond 60% of the page width.
4. Repeat footer checks as described in step four of the Home section 
5. Review of all functionality and responsiveness on mobile screen size by using <a href="https://www.responsinator.com/">Responsinator</a>

## Development

This project was developed using the IDE Colud9. Updates to the project were committed to git. These updates where then pushed to GitHub where they were stored in a public directory.

Committing and pushing updates was done through cloud9s inbuilt functionality.

To deploy these pages to GitHub pages for the GitHub repository, the following method was used.
1. Logged into my GitHub account (https://github.com/DarrenCoppinger)
2. Go to Repository tab.
3. Click the repository called "playwright-milestone-project"
4. Go to the "Settings" tab at the top of the page and click it.
5. Scroll down the "Settings" page to the "GitHub Pages" section.
6. In the "Sources" subsection select "Master Branch" from the drop-down menu currently labelled none. This refreshes the page and publishes the project.
7. Scroll down again to the GitHub pages section to find a link to the deployed website.


### To Run Project Locally

To clone or copy this project from GitHub follow these steps:
1. Follow this link to the [project repository on GitHub] (https://github.com/DarrenCoppinger/playwright-milestone-project)
2. On the left side of the page click the green button labelled "Clone or Download"
3. In the pop up that appears labe;led "Clone with HTTPs" section copy the URL
4. In your local IDE open Git Bash
5. Change the working directory to the to the location for the cloned directory to be stored.
6. Type "git clone" and then paste in the URL copied from GitHub in step 3
7. Hit enter and create your local drive.


## Credits
### Media
The photos on the site were provided by the client. Where indicated certain images are used with permission of the copywrite holders, Laura Sheeran and Claudia Marinaro.

### Content
The pdf extracts of the playwright's work (Townland and The Minimum Requirement) accessible from the "Writing" page and the text used on the "About" page were provided by the client, Playwright Neasa O'Callaghan.

### Acknowledgements

I would like to thank Neasa O'Callaghan for her input into this design and for providing the image, video and audio content for it.

#### Disclaimer

This Website was produced for educational purposes only.
