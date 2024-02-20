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
