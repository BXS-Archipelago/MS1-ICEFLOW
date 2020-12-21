======================= iceflow by Brian Smyth =======================



## === Overview-====

This website is for any contemporary music enthusiast and will provide them with direct links to singer-songwriters of the Nordic Music industry. 

### Why does it exist

There are many artists in the Nordic region who create their music in the English language, however the marketing strategies of their record labels often do not extend properly into the global market. This website will act as a relay for the artists to introduce their music to a wider audience, especially in Europe and the US. 

Commercial radio stations only exist commercially, so music that is off the radar does not interest them and does hold a commercial value for them. Music enthusiasts mostly find reference to hidden talent through independent means, such as word-of-mouth, the artists' self-promotion and through independent resources. This website is created as an independent resource for the artists featured herein. 

### What does it do?

The site will provide some biographical information for each artist, with links to their work provided through YouTube and spotify links, and also direct links to the artists' social media pages. 

### How does it work?

The landing page will contain a gallery that will in turn open to the individual artist's page on the site. A visitor will be able to explore the resources contained, such as biographical and discographical information,  music from embedded Spotify playlists and embedded YouTube videos. 


### Who will benefit most from visiting the site

- Music enthusiasts.
- English speaking
- Commuters
- Students
- Anybody who uses earphones with their mobile devices
- Music is proven to improve mood, reduce stress and/or anxiety, improves  exercise and performance, improves memory and cognition. The site has broad application and will benefit a wide demographic, age 17 to 55. 

### How is it made?

The site is designed using only HTML5 and CSS3 with some Bootstrap. There is a high potential for development with Javascript at a later stage though. 

## User Experience 

Visitors to the site are looking for new music experiences from unfamiliar artists. They will be invited to browse each artist and listen to samples of the music on spotify or watch YouTube videos.

There are links to the artist's live shows and also icon-identifiers for their social media pages.

Alternatively, they can listen to a Spotify playlist from the gallery without entering and reading the page.

There are countless websites for music and artists out there, but few if any exist that compile an active list of Nordic performers. The site will initially contain contemporary female artists of the past three decades, but will expand to include male singers and also groups.

With the scope for so many artists, the site must remain easy to navigate. Other sites can be a compendium of categories and sub-categories with separate blogs and ancillary pages. This site will be: - Easy to understand - simple navigation - simple external links to open separately - Subtle effects for site elements and concise single-page biography and discography, with sample video and playlist for perusal.

The site owner actively populates the social media pages with new entries so the visitors will be encouraged to click to their favourite site, for example, Facebook, Twitter, Instagram.

#### Wireframes
A Wireframe mock-up has been created with Balsamiq to show an approximate visual objective for the site and is contained in the assets folder: 

/workspace/MS1-ICEFLOW/assets/iceflow_Wireframe.pdf

## Viewing the Site Responsively
#### Desktop
Each page will contain a logo in the top left screen that will also provide a home link to index.html.

A responsive navigation menu will sit to the top right of the screen on tablet and smaller screens

Logo and navigation menu will be contained in a row with a 4 and 8 unit column width therein.

Each page will contain a footer that will house the site's associated Social Media links along with a brief site-summary, listed links to the Nordic countries (at a later time, this will serve as a cross-reference index for each artist listed country by country.)

The pages' background image will be a neutral off-white colour to contrast with the elements colours and shadow effects.

Landing page - index.html -will contain a brief summary of what the site is about, along with new concert information and new album releases that are relevant to the featured artists.

Artists page - artists.html - will contain the responsive main gallery of artists. Each image is animated upon hover to slide upwards to reveal the name, brief summary. The visitor can pick to either listen to the suggested Spotify list or else click into the artist's own page for full detailed information, video, playlist link or to view their albums and concert information.

The About page will give a brief summary of two things : firstly, who the featured artists are and why we focus on them. And secondly, a paragraph for the purpose of the site.

The Contact page will contain an online form where the visitor can submit their name, email address, their country and a short message to the site owner.

Both the About and Contact page will encourage the visitor to send in the name of their favourite artist or somebody not already featured on the site.

The pages for the artists will contain a short biographical note, a section for recommendations of their work to the visitor, with link to spotify and a featured Youtube video from the artist.

#### Tablet View
The tablet view will inherit most features of the desktop site but the navigation bar will respond by transforming into a Burger bar for a drop-down menu. This will feature in the top right.

The Burger bar, when activated will transform into a "X" that can close the menu if required. This will be seated near the top right of the page.

#### Mobile view
On mobile phone devices, the nav bar will remain as an active Burger-style drop-down menu.

The Landing page gallery will shrink to a single column to scroll downwards.


## Design
Header - Logo will be text-based, the site name : "iceflow"  

Logo font-family : "Roboto Condensed", a simple font to keep with the theme of the site as a publisher of information. I want to avoid serifs or any text decoration apart from simple sizing and bold-effect where required. 

## Color-scheme -

Color palette:
- Neutral background, light & clean : #EFEFEF
- Feature Colour : Deep Carbon : #A9A9A9
- Feature Colour : Metallic Gold: #D4AF37
- Dark Contrast for Footer : #26272b;




## Pages and folder List

- - assets (folder)
- - css (folder)
-  style.css
- - img (sub-folder)
- index.HTML 
- artists.html 
- about.HTML 
- contact.HTML 
- artist-template.html (name will change with each entry)


## Building the site
The Navigation bar:

The initial step was to use Row & Column 4 & 8 for the logo and navigation bar area. This produced other issues with overall page margins and padding, so I removed that layout from the header.

Rather than use a source-code template for the Navigation, I followed a video tutorial to gain the effect I wanted. Most were using JS or else were very basic looking. I chose one that will include a rotating menu icon with transitions on the page title to add extra life to the effect, but using only HTML and CSS.

With Font-choice for the logo and menu (compared to the turorial instructions), the paddings and margins needed to be set very differently. The Hamburger icon was widened with further adjustments to the - Transform:TranslateY - settings to ensure the animated X kept a centered cross-over of the first and third bars (the middle one removed using opacity).

The main body uses Container, Rows and Columns with separate sub-containers for each news section. Each section was given strong contrasting colours to make it eye-catching.

The footer also uses Container, Rows and Columns to fit all the information. It contains site information, a list for the Nordic countries, Quick links and also the site's own Social Media links in icon-identifiers.

The Gallery - artists.html. The video tutorial for the effect was originally intended for just three Cards of a long rectangular shape. I re-sized the photos to make them suitable for the container, also adjusting the size of the card. The inside card was edited to fit the shrunken picture evenly at the top with the text, divider and buttons all repositioned. The objective of this was to make them as appealing as much in mobile view as it is on desktop. 


## Validation: 

    The CSS was tested at the W3C [Validator](https://jigsaw.w3.org/css-validator/validator) and was found to have no issues. 

    The HTML pages were validated at the W3C HTML [Validator](https://validator.w3.org/)

    No issues were found in my own code, however the validator found the Youtube and Spotify frameborder on the iframes to be obsolete. This is from the embedding code provided by both YouTube and Spotify. 

    ![youtubespotify](https://user-images.githubusercontent.com/71372294/102778214-1746dd00-438a-11eb-9285-84d71b658295.png)


## Bug Reporting: 

 As above, the W3C validator pointed out obsolete methodology used in the embedded code from both YouTube and Spotify. From researching the error, it seems that W3C are reviewing the standards for this problem. 

    Following intensive testing, the page passed requirements for responsiveness on all screens. 

I found one bug, however, in the contact.html page that I found challenging to overcome and in the end I had to change the design. The issue was as follows:

    Contact Form contains fields with <span> set for field names such as name, country, email, etc. 
    When the visitor clicks on the line, field name rises in transition to leave a blank line for the information to be entered. 
    As input-type="text for the email section, the translate(Y) movement worked perfectly. However the email was not able to be validated. 
    As input-type="email", the information was validated, but the Translate(Y) movement returned to its original point, leaving text over text, and so it is unreadable. 
    This is a CSS rule conflict, so I was unable to provide both the attractive text movement and the email validation without using Javascript. This was a disappointment as I had spent several hours trying overcome the issue and the original display suited the site very well.


## Credits
Navbar -
Video tutorial for animated bar for responsive navigation menu: Creator : Tech2etc https://youtu.be/baFqcVUMUg0

## Gallery --
Video tutorial for animated holding card for artists' photos and button: Creator : Tech2etc https://www.youtube.com/watch?v=L5c6P1edZvE&t=315s

#### Contact Form --
Contact page tutorial for the contact form :
Creator : Online Tutorials
https://www.youtube.com/watch?v=gggB0Nq5vBk

#### Photograph Credits --  
gig2.jpg  Microphone photo created by Oscar Keys; 
Source Unsplash.com
https://unsplash.com/photos/ojVMh1QTVGY

guitars3.jpg  Music room photo created by Wes Hicks; 
Source Unsplash.com
https://unsplash.com/photos/MEL-jJnm7RQ

records.jpg created by Eric Krull ;
Source Unsplash.com
https://unsplash.com/photos/fi3_lDi3qPE

Contact page - Singout.jpg photo created by Alyssa Yung
Source Unsplash.com
https://unsplash.com/photos/-Gx7tuwO8_U

### ****** NB - Photographs of the individual artists ******
Images of each artist were taken from the artists own website or social media page. The creator's name for each photo was not available but the images are in wide circulation as marketing material. 


## Responsiveness of  Display


The following Browsers were checked to ascertain whether the site was in optimal display in all sizes. 

Responsiveness and sample-page copies from the site on different screens. 

#### Generic Laptop : 
![Bxs-archipelago - Generic Laptop - 2020-20-12 at 1 02 59 PM](https://user-images.githubusercontent.com/71372294/102714047-311dec80-42c4-11eb-8d1b-ac205ff79f8c.jpg)


![Bxs-archipelago - Generic Laptop - 2020-20-12 at 1 03 29 PM](https://user-images.githubusercontent.com/71372294/102714057-40049f00-42c4-11eb-90d7-afac6e8b4fad.jpg)

#### iPhone display

![Bxs-archipelago - iPhone X - 2020-20-12 at 1 02 47 PM](https://user-images.githubusercontent.com/71372294/102714080-590d5000-42c4-11eb-9da3-dbcfed76d265.jpg)
![Bxs-archipelago - iPhone X - 2020-20-12 at 1 03 21 PM](https://user-images.githubusercontent.com/71372294/102714096-632f4e80-42c4-11eb-85f1-a4e4103ef5a0.jpg)

#### iPad display

![Bxs-archipelago - iPad - 2020-20-12 at 1 02 55 PM](https://user-images.githubusercontent.com/71372294/102714069-498e0700-42c4-11eb-80dc-5cbf7b1bae33.jpg)
![Bxs-archipelago - iPad - 2020-20-12 at 1 03 26 PM](https://user-images.githubusercontent.com/71372294/102714072-501c7e80-42c4-11eb-9108-2d3ad67967eb.jpg)



## Further Testing:

The site was also checked across browsers and several different devices on www.browserstack.com

![iceflowtest](https://user-images.githubusercontent.com/71372294/102820960-0fa92780-43ce-11eb-9600-99300ffdc763.png)



## Deployment

The website was hosted on GITHUB while built in the gitpod collaborative development environment. 

### Published: 

The current hosted address for the site is: 

 https://bxs-archipelago.github.io/MS1-ICEFLOW/

## Forking

We welcome review and constructive input for the ICEFLOW pages using GITHUB to our mutual benefit. 

This can be done using your GITHUB login and going to the Repository( https://bxs-archipelago.github.io/MS1-ICEFLOW/) for our site. 


## Cloning

To clone the site, please use your GITHUB login and find : 

The Repository( https://bxs-archipelago.github.io/MS1-ICEFLOW/)  

- Click the "Clone or Download" button.

- Use the Link at "Clone With HTTPS"

- Open a new Terminal and go to your chosen directory.

- Use the Command - "git clone" and paste in your previously copied link.

- Hit Enter to Clone.



## Future Potential:

Iceflow has the potential to become a popular music media site. Driven by Social Media, the site visits could generate revenue through advertising and affiliate marketing. There is scope for two to three hundred featured artists with more sophisticated indexing system such as by genre, by country, by gender, and other sub-categories. 

This would inevitably need javascript development, (especially for the bug in the contact form) but for the sake of this MS1 project, I chose to limit the content to HTML5 and CSS3 since that has been the subject matter of the course thus far. 


