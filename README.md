# Daily Life of Anne Boleyn
Daily Life of Anne Boleyn is a website that sends out a daily, weekly, or monthly email to the user about what happened to Anne Boleyn 500 years before. It also contains biographical information on Anne Boleyn, and a page containing all of the media appearances that include her as a character. 
The intended user base for this website is people who are interested in history, and wish to learn more about the Tudor period. There is a question on the form page about whether users would be interested in other prominent Tudors, to see if there is a market for expansion.
![Image showing webpage on different size devices](assets/images/am-i-responsive.png)

# Features
## Navigation Bar
![Image showing the mobile navigation bar](assets/images/navigation-bar-mobile.png)

![Image showing the navigation bar](assets/images/navigation-bar.png)

The navigation bar is available in the same order on all pages to make for ease of navigation. On mobile it is under a burger icon so that it takes up less space and can be opened and closed as required. On larger screens it is fixed to the top to make for easy scrolling. It is the same colour as the header, except for the open page, this is to ensure ease of navigation.

## Index Page
![Image of index page](assets/images/index.png)
The index page is a simple page, with an image of Anne Boleyn, and a description of what the page's intent is and why. This includes the most famous painting of Anne, to be eyecatching.
## Footer
![Image of the footer](assets/images/footer.png)

The footer gives a simple email address to contact with further questions. This is for ease for the user.
## About Anne page
![Image of the about page](assets/images/about-anne.png)

The About Anne page is a brief overview of Anne's life. The first five sections are about Anne's life, with relevant images. On mobile the images are under the headers, whilst larger screens they are on the left. This was important to include as it gives users an idea about who Anne was and her importance to history.
## Children Section
![Image of the Children section](assets/images/about-children.png)

The children section is part of the about page as it helps apply context to Anne's importance in history, including after her death. The information about Elizabeth also links into the question later on the form querying if information about other Tudors would be of interest as it gives an example. 
## Map
![Image of the map](assets/images/map.png)

The map gives the location of where Anne is buried. 
## Media Page
![Image of the media page](assets/images/media-page.png)

The media page lists all of the actresses who have played Anne, including the name of the works and the year. This is so that if the user wishes to watch anything they have an easy place to find all of the onscreen portrayals of Anne.
## Video
![Image of the video section on the media page](assets/images/video.png)

The video is complete with controls so that the user can choose if they wish to interact or not. The video is of the West End/Broadway show portrayal of Anne.
## Form
![Image of form](assets/images/form.png)

The form takes the name and email address, and won't submit unless these are correctly input. It also asks how often the emails should be sent for the user's preference, as well as if they'd be interested in other Tudors, to see if expansion would be a useful feature to implant in the future.

# Testing

## Lighthouse
I have run all pages through Lighthouse, both mobile and desktop, to ensure fully accessable. Has come back on all pages as 100.

### Header
For the header, on mobile screens, the navigation bar is beneath a burger icon that has to be clicked on in order for the options to come up. This saves space on smaller devices. On a tablet or desktop, the navigation bar is fixed to the top of the screen as this has more space. The header text is set to be central on all screen sizes, but with different font sizes in order to fit the type of device.

### Index Page
The image on the index page is responsive to screen size. The text on larger screens also increases in size.

### Who Was Anne page
Each section is underneath a clear header for navigation. Each section contains a header, text about the subject, and a relevant image. On a mobile screen, the image appears between the header and the text, on a tablet or a desktop it appears to the left side. 

### On-Screen Portrayals
Each div contains an image of the actress, and some text. On a mobile screen this is a single column, with the picture above the text. On a tablet sized screen, these are in rows of two, and on a desktop, this is in rows of three. On each sized screen there is a hr line between each row.

## Second Opinions
After the main pages had been created, I showed this to a relative for their opinions on if this was logical and what they would expect from a website. 
* Children page - at the time, the information about Elizabeth was on a separate page. The feedback advised that this was better suited on the Who Was Anne page as it is not a main focus for the site and also shows the longer impact Anne had on history.
* Wives page - there had originally been a page about the six wives of Henry VIII. The feedback was that this was a little redundant, especially as Catherine and Jane's significance to Anne was featured on the Who Was Anne page, and the other three had no real connection. Because of this, I removed this page, however did use the responsive coding on the media page.
* Sign Up form - on the navigation, this was the second link. It made more sense for this to be the last one, and so I moved this
After these changes were made, they agreed that the website made more sense to read
* Spacing - Some of the spacing wasn't big enough, and made for difficult reading. Because of this I added padding and margins.
* Font - in some places, such as the middle of an H, the font was too thin for this to be readable. Because of this, I increased the font weight.

## Bugs
### Footer
The footer would not remain at the bottom of the page. On the main and sign up page, it would go to the bottom of the text, and on other pages appeared about halfway down. There was also a horizontal scroll bar, despite nothing to scroll. Setting the position for the index and sign up page did make this appear nearer the bottom, however there was still some space beneath this. Eventually, setting the footer as a flexbox, I was able to get the footer to remain at the bottom. I also removed all margins to remove the space. The issue with the scrollbar was caused by the width of the header.

# Deployment
This was deployed to GitHub pages
* Clicked onto the settings tab, and then onto *Pages* under *Code and automation*
* Ensured Branch was set to *Main*, and saved
* Located under *Environments*
The deployed site can be located here: https://bryonyrblack.github.io/anne-boleyn/index.html

# Credits
## Content
* Footer pushed down, code from Love Running
* Historical Facts from Tudors by Peter Ackroyd
* Mobile Navigation bar from Love Running
* Icons in the navigation bar from Font Awesome

## Media
* Images used are from Google Images, with license set to Creative Commons licenses
