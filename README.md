# Leger Shearings Interview Task 3

## Table of Contents
1. [Idea](#idea)
2. [Images](#Images)
3. [Design](#design)
4. [Sources](#sources)
5. [Testing](#testing)


## Idea




## Images
### Adobe Stock
* [St. Peter's cathedral at night, Rome](https://stock.adobe.com/uk/images/st-peter-s-cathedral-at-night-rome/44298623)

* [Panoramic view of the Roman Forum, Rome, Italy](https://stock.adobe.com/uk/images/panoramic-view-of-the-roman-forum-rome-italy/179316308)

* [Piazza de spagna(Spanish Steps) in rome, italy](https://stock.adobe.com/uk/images/piazza-de-spagna-spanish-steps-in-rome-italy/276263924)

### PixaBay

* [Italy Florence Church](https://pixabay.com/photos/italy-florence-church-tuscany-4256018/)

* [Venice Canal](https://pixabay.com/photos/venice-italy-city-urban-travel-2686292/)

* [St Peter's Basilica Vatican City](https://pixabay.com/photos/rome-st-peter-s-basilica-vatican-5778178/)


## Design
![Photoshop Design and Layout](assets/design/shearings-destination-page-andrew-harding.jpg)



## Sources
* [Tiny PNG](https://tinypng.com/) Used to compress image sizes.

* [Adobe Stock](https://stock.adobe.com/uk/) Used for some images.

* [Pixabay](https://pixabay.com/) Used for some images.

* [Code Institute Gitpod Template](https://github.com/Code-Institute-Org/gitpod-full-template) Adds the Emmet abbreviation to the workspace. 

* [Bootstrap Grid](https://getbootstrap.com/docs/4.0/layout/grid/) To get the layout of images and text to the left and right.

* [Google Fonts](https://fonts.google.com/specimen/Mulish?query=mulish) After inspecting the Shearings code I could see that they were using the Mulish font from Google Fonts. I headed over to Google fonts to get the links and apply this to the page.

* [Favicon](https://shearings.imgix.net/Content/Shearings/images/favicons/apple-touch-icon.png) I originally made a copy of the Shearings Favicon, but upon inspecting the Shearings website I found there was a link to a better higher quality favicon that they use for their site, so I used the lik for this insetad.


## Testing
When viewing my page with the blue destination box and white space (for the images that dont have a box) at first  was showing either side of the image as shown below. 
![Blue box and white space](assets/images/testing/before-col-lg-targeted.jpg)
At first when I inspected the column in Google I thought it could be the image size, but this was not the issue.

Upon further inspecting and tartgeting the blue box in Google I could see that the SCSS with the col-lg padding right and left was set at 15px. Unticking the box meant that the blue box space on the left of the image, and where the image has no box the white space to the right of it were removed. I went into my CSS file and added the .col-lg with the padding-left and padding-right of 0 and this gave me the expected result that I was after.
![Blue box and white space gone](assets/images/testing/col-lg.jpg)