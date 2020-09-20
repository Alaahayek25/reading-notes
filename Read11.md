# imges:

### Today we will learn some light and easy-to-use information in practice in Css.
- You can control the display of images by selecting the image
   To be changed
   -  For example:
> small..
>medium..
>large...

HTML
```
<img src="images/magnolia-large.jpg"
 class="large" alt="Magnolia" />
<img src="images/magnolia-medium.jpg"
 class="medium" alt="Magnolia" />
<img src="images/magnolia-small.jpg"
 class="small" alt="Magnolia" />
 ```
 CSS
```
img.large {
width: 500px;
height: 500px;}
img.medium {
width: 250px;
height: 250px;}
img.small {
width: 100px;
height: 100px;}
```
## Background Images
we can applies background image just to a paragraph bu this way p { background-image: url(“images/pattern.gif”);}


#### Background Position
When an image is not being repeated, you can use the background-position property to specify where in the browser window the background image should be placed.

by Clockwise direction the orderd position are

1. left top
2. left center
3. left bottom
4. center top
5. center center
6. center bottom
7. right top
8. right center
9. right bottom



### Flash, Video and Audio
Flash was once a very popular technology used to add animations, video and audio. All files created in Flash are referred to as Flash movies. These are created in a Flash authoring environment by Adobe. To be able to view these additions on the website, users need to install flash plugins and flash players. Flash movies have been replaced with the introduction of video sharing sites and HTML5.

### what is FTP?!

FTP allows you to transfer files across the Internet from your computer to the web server hosting your site. For example;

FileZilla

filezilla-project.org Windows, Mac, Linux

FireFTP

fireftp.mozdev.org Windows, Mac, Linux

CuteFTP

cuteftp.com Windows, Mac
