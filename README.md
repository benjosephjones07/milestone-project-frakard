# Frakard Website

View live project [here](https://benjosephjones07.github.io/milestone-project-frakard/)

This is the website for musical artists, Frakard. It is designed to be responsive and accessible on a range of devices, making it easy to navigate for new fans, long time listeners, and music lovers looking for more information.

![frakard mockups](assets/images/frakard-mockups-2.png)
---
## User Experience (UX)

* ### User stories

    * __First time visitor goals__
        * (a) As a first time visitor I want to be able to see, hear and 'experience' the band.
        * (b) As a first time visitor I want to be able to intuitively use the website and find the content that I'm looking for.
        * (c) As a first time visitor I want to easily find the band's social media links in order to find out about what they are doing currently and in the future.

    * __Returning visitor goals__
        * (a) As a returning visitor I want to be able to contact the band for various reasons.
        * (b) As a returning visitor I want to be able to hear different songs from the band.

    * __Frequent user goals__
        * (a) As a frequent user I want to keep up to date with live appearances that the band are making.
        * (b) As a frequent user I want to quickly see what the band are pushing/most proud of right now.

* ### Design

    * __Colour scheme__
        * The two main colours used are white and frakard burgundy, with a darker shade on the hovered desktop links.

    * __Typography__
        * The main font used throughout the site is Raleway, with sans-serif used as a back up incase an error occurs with the google fonts CDN. Raleway was used for its similarity in appearance to the band logo and general aesthetic compatilibility with the website.

    * __Imagery__
        * The websites most eye catching feature is the full screen sized background image of the band in live performance, with a dark overlay on it. The band are very much a 'live band' and wanted this to be the main feature of the website, and what people will first see when they visit. The dark overlay and darker colours used throughout correspond to the darker and heavier musical style of the group.

    * __Layout__
        * The website has been designed with several unconventional design choices in mind. This is to go along with the sense of unconventional artistic originality that is important to the band. For example, the content on each page has been centered, with the links to social media directly to the side of the main content. There is also very little written content in terms of description of the band - this is to preserve a sense of mystery around the band and let the music stand on it's own without preconceived notions.

    * __Minimalism__
        * The website has been designed according to the principles of the currently popular ethos of minimalism. This includes cutting out additional details, a simple colour palette, and lots of empty space. It is for this reason that the headings on each page are hidden (yet still included in the code for SEO and screen reader compatibility). 

    * __Progression from wireframes__
        * As can be seen below, the wireframes were adhered to quite rigidly, with the exception of music.html. Once construction on the site began it was decided by the developer that the coverflow design was for the moment beyond his capabilities and would prove too time consuming.

* ### Wireframes

    * Home page wireframe - ![homepage wireframe](assets/images/home-wireframe.png)
    * Music page wireframe - ![music page wireframe](assets/images/music-wireframe.png)
    * Video page wireframe - ![video page wireframe](assets/images/video-wireframe.png)
    * Gigs page wireframe - ![gigs page wireframe](assets/images/gigs-wireframe.png)
    * Contact page wireframe - ![contact page wireframe](assets/images/contact-wireframe.png)

## Features

* Music player from Spotify
* Video presentation from Youtube
* Current gig listings
* Contact page
* Responsive on all devices
* Interactive nav bar

## Technologies used

### Languages used

* HTML5
* CSS 3

### Frameworks, libraries and programmes used

1. [Bootstrap 5.0](https://getbootstrap.com/) was used to assist in styling and responsiveness
2. [Google fonts](https://fonts.google.com/) was used for typography
3. [Font awesome 6.0](https://fontawesome.com/) was used for icons throughout
4. [Spotify](https://www.spotify.com/uk/) was used to embed an iframe containing a music player on music.html
5. [Youtube](https://www.youtube.com/) was used to embed an iframe containing the music video for the band's latest single on video.html
6. [Git](https://www.gitpod.io/) was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub
7. [Github](https://github.com/) was used to store the code after being pushed from Gitpod
8. [Balsamiq](https://balsamiq.com/) was used to create the wireframes

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

* W3C HTML validator results - ![HTML validator results](assets/images/html-validator.png)
* W3C CSS validator results - ![CSS validator results](assets/images/css-validator.png)

The validators flagged up a few errors that came with the iframes embedded from Spotify and Youtube. Their code contained outdated html that needed to be corrected, including incorrect html height and width units.

### Testing User Stories from User Experience (UX) Section

* __First time visitor goals__
    * (a) to be able to see, hear and 'experience' the band.
        * When you first visit the website you are greeted by a fullpage image of the band allowing you to see them. Within one click you are taken to the music page where you can hear the band. Within one other click you are taken to the video page where you can experience the band performing live.
    * (b) to intuitively use the website and find the content that I'm looking for.
        * The website has a minimal amount of pages that are all straight forwardly titled to aid in navigation. The navbar is simple and eye catching which further aids in this. 
    * (c) to easily find the band's social media links in order to find out about what they are doing currently and in the future.
        * The 3 primary social media links the band uses are prominently displayed on the home page, and purposefully right next to the main content on each of the remaining pages.

    * __Returning visitor goals__
        * (a) to be able to contact the band for various reasons.
            * contact.html is clearly visible in the navbar at the bottom of the page. The text prompt 'What's on your mind?' is general and inviting to the user.
        * (b) to be able to hear different songs from the band.
            * On the music.html page is a Spotify music player where the user can find several songs snippets from the band. If the user is logged into their Spotify account then they can hear the full song. This player updates according to the most popular songs from the band on Spotify.

    * __Frequent user goals__
        * (a) to keep up to date with live appearances that the band are making.
            * gig.html is clearly visible in the navbar at the bottom of the page. The gig listings present on this page will be regularly updated and added to.
        * (b) to quickly see what the band are pushing/most proud of right now.
            * In the bottom center of the home page is a callout that currently says 'Debut single 'Dogs Dinner' out now'. This immediately notifies the user of what the band are currently promoting, and will be periodically updated. 

### Further testing

* Through Google Chrome Dev tools the website was viewed on a variety of devices such as Desktop, Laptop, iPhone7, iPhone 8 & iPhoneX.
* The links between pages on the navbar were tested thoroughly to ensure that they all work.
* Friends and family were consulted and asked to use the website to further ensure of the websites strong functionality.
* Some difficulty was encountered between the usage of Bootstrap functionality and custom CSS stylings, where undesired and unexpected outcomes occured, especially when attempting to centre certain sections of the website, and in mobile responsiveness. The decision was eventually made to use Boostrap as the foundation of the website, and custom CSS only when needed.
* The Lighthouse feature on Google's dev tools was used and the site was edited accordingly. For example, alt text was added to the social links icons, "noopener" tags were added to them also to help ensure safety and conformity to best practise, and a meta description was added to the head of each page to improve SEO.

![Lighthouse report](assets/images/lighthouse-report.png)

## Deployment

### The project was deployed to Github using the following method:

1. Login to Github and find the correct Github repository
2. At the top of the repository click 'Settings'
3. Scroll down the settings options until you get to the 'Github pages' section, click 'Check it out here!'
4. On the source dropdown menu, select 'main'
5. The page will automatically refresh, then click save.
6. Scroll back through the page to locate the now published site link in the "GitHub Pages" section

## Credits

### Code

* Bootstrap 5 was used frequently throughout project development for the purposes of responsiveness and grid system layout.
* [This](https://github.com/Code-Institute-Solutions/SampleREADME#code-institute-website) Code Institute README.md template was consulted and tailored during the writing of this README.md file for the purposes of structure, typical README.md contents, and boiler plate materials.

### Content

* All content was written by the developer.

### Media

* The background image was taken by Gabe Jones with usage rights belonging to Frakard.
* All other images were created by the developer.

### Acknowledgements

* My Mentor Anthony Ugwu for help particularly in the early stages of development.
* Code Institute Tutor support for continuous practical tips and advice.
