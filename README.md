# IntroToHTML&CSS
-------------------------------------------------------------------------
# HTML
-------------------------------------------------------------------------
HTML 
- HyperText Markup Language
- Base of a website
CSS
- Casading style sheets
- Style a website
- Fragile and powerful
Javascript
- Add Functionality to a website
- Resilience, robustness and power to their websites
-------------------------------------------------------------------------
<article>
  <p>paragraph</p>
  <em>emphasized</em>
  <h1>Biggest Heading</h1>
  <h6>Smallest Heading</h6>
  <strong>Bold text</strong>
</article>
-------------------------------------------------------------------------
<ul>
  <li>Bullet point</li>
</ul>

<ol>
  <li>Numbered</li>
</ol>
-------------------------------------------------------------------------
                yyyy-mm-dd
<time datetime="2025-05-08">May 8, 2025</time>
                hh:mm:ss.dd
<time datetime="14:15:28.5">May 8, 2025</time>
-------------------------------------------------------------------------
<pre>This text will incude           a gap on the website</pre>
-------------------------------------------------------------------------
<p>H<sub>2</sub>O</p> H20 (small 2 lower)
<p>4<sup>2</sup></p> 4x4=16 (small 2 upper)
-------------------------------------------------------------------------
<p class = "CLASS">This is a class that identifies MULTIPLE</p>
<p id = "ID">This is an ID that identifies ONE</p>
<!-- This is a HTML comment -->
-------------------------------------------------------------------------
      This is to add controls under the video
            |
<video controls> 
  <source src="VideoSource.mp4">
</video>

<img src = "ImageSource.jpg" alt="Logo" width="400" height="400">
--------------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>   <!-- The head contains metadata, every website consists of this format -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <!-- This is the body which contains most info of the website -->
</body>
</html>
-------------------------------------------------------------------------
HTTP
- Hypertext Transport Protocol
HTTPS 
- Hypertext Transport Protocol Secure
-------------------------------------------------------------------------
"blog/march-9.html" for a source would first look in the current flder for a folder called blog and then the file march-9.html
-------------------------------------------------------------------------
<nav> <!-- This is a simple example of a nav bar using only HTML-->
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>
-------------------------------------------------------------------------
<footer> <!-- This is a simple example of a footer using only HTML-->
    <p>Copyright © 2024 YourWebsite. All rights reserved.</p>
    <p><a href="#privacy-policy">Privacy Policy</a></p>
</footer>
-------------------------------------------------------------------------
GIF
- supports 256 colurs
- look pixelated
SVG
- logos, icons, etc
- vector 
- prog lang for graphics
JPG
- most popular
- can be compressed
PNG
- for transparency
- better than jpg and gif for compressing
- future proof
-------------------------------------------------------------------------
<!-- srcset is used to choose whoch image to display depending on the user's device resolution (2x, 3x, 4x, 1.5x) -->
<img src="example.jpg" 
     srcset="example@2x.jpg 2x, 
             example@4x.jpg 4x"
     alt="Example Image">
-------------------------------------------------------------------------
<!-- This is used to create a caption for an image, not both figure and figcaption elements were used -->
<figure>
    <img src="example.jpg" alt="Example Image">
    <figcaption>This is an example image caption.</figcaption>
</figure>
-------------------------------------------------------------------------
  "controls" is to add controls to the audio
          |
<audio controls src = "audio.mp3"></audio>

<iframe src="https://www.example.com"></iframe>
-------------------------------------------------------------------------
<!--example of a login form-->

<!-- method = get is for javascript to add the functionality
label is the text next to the textbox
input is the textbox which needs a type, id, name and a "required" tag for validation
placeholder is used to add an example to the textbox -->

<form action = "eg.html" method="get">
    <label for="username">Username:</label> 
    <input type="text" id="username" name="username" required><br><br>
    <label for="password">Password:</label>
    <input type="password" id="password" name="password" required><br><br>
    <input type="submit" value="Login">
</form>
-------------------------------------------------------------------------
<!-- This is an example of a table
th = table head
tr = table row
td = table data
-->
<table border="1">
    <caption>Employee Information</caption>
    <th>
        <tr>
            <th>ID</th>
            <th>Name</th>
            <th>Position</th>
        </tr>
    </th>
    <tr>
         <td>1</td>
         <td>John Doe</td>
         <td>Manager</td>
    </tr>
        <tr>
          <td>2</td>
          <td>Jane Smith</td>
          <td>Developer</td>
        </tr>
        <tr>
          <td>3</td>
          <td>Emily Johnson</td>
          <td>Designer</td>
        </tr>
</table>
-------------------------------------------------------------------------
# CSS
-------------------------------------------------------------------------
Selector
|  Property  Value
p {  |       |
    Color: red;
}

Color themes: https://www.canva.com/colors/color-palette-generator/

IDs
- Individual names
Classes
- Could have same name

Hex Values start from 0-9 and a-f

Box Model
- Margin
- Border
- Padding
- Content




























-----------------------------------------------
Units 5-8 HTML rev
-----------------------------------------------
src in image tag is the image url
alt is alternative text for the image
describe the image in the alt section 

image needs to be in file format in order for the web browswers to understand
its best to aim for highest quality with the least size
-----------------------------------------------
each image format has different ways to compress them, here are 4 formats:

GIF
compressing illustrations, supports 256 colours
might look pixedlated
can be transparent but might have jagged edges

SVG
commonly usd for illustrations
is a vector
prog lang for graphics

JPG
compressing photographs
resize and compress is neccessary
can be compressed at the price of color information

PNG
Great for transparency
PNG > GIF and JPG in compressing certain images
-----------------------------------------------

CSS used for responsiveness in images
HTML can be used to deliver different images based on screen sizes

Always give the browser more info if the image is small

srcset is used to provide a different set of images based on your density and viewport width using 1x, 1.5x, 2x and 4x, or 480w 960w, etc
srcset="elva-fairy-480w.jpg 480w, 
        elva-fairy-800w.jpg 800w"

Image demo size from 27k to 593k

<figure>
  <img src="ewfbmpov.jpg" ............>
  <figcaption>This is the figcaption that is under the image</figcaption>
</figure>

controls in audio tag gives the play button, timeline and volume control.

audio tag has an open adn closing tag 
<audio controls>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
  Your browser does not support the audio tag.
</audio>

video tag aswell has an opening and closing tag
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video>

H.264 is a video codec and is NOT open source and is owned by CONSORTIUM

AV1 might overtake H.264 and is free and can be used for images and audio

----------------------------------------------------------
#CSS
----------------------------------------------------------
select class (.class)
HEX colors are 6 digits long consisting of num 0-9 and A-F
It can also be 3 digits if it has repeating digits in them (#7778899 -> #789)
Opacity could also be stated in the rgb value at the end of the set of numbers (rgba(119,136,153,0.8) 0.8 is the opacity)

GIF 
256 colors
Transparent
Animation
Illustrations

PNG
16m colors
Transparent
Ilustrations

JPG
16m colors
Photo

WEBP
new
high compression

Absolute - Don't change with screen size:
Points
Pixels

Relative - Changes with screen size
Percentage
Rems

Box model from inside -> out
Content 
Padding
Border
Margin

Border-radius: 50%; for circle image










