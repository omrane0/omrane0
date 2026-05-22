
<!---
omrane0/omrane0 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
-  ✔️  https://github.com/omrane0
-  📕 https://gitlab.com/omrane0
-  💼 https://sites.google.com/view/fayca

01.  HTML Images 

https://www.w3docs.com/tools/editor/29
Place for your heading
This is Aleq's photo


<!DOCTYPE html>
<html>
  <head>
    <title>Title of the document</title>
  </head>
  <body>
    <h1>Place for your heading </h1>
    <p>This is Aleq's photo</p>
    <img src="/uploads/media/default/0001/01/25acddb3da54207bc6beb5838f65f022feaa81d7.jpeg" alt="Aleq" width="200" height="185"/>
  </body>
</html>




02.  Obtenir la date actuelle

<html>
<head>
    <title>PHP Get Current Date</title>
</head>
<body>

<?php
// Return current date from the remote server
$today = date("d/m/Y");
echo $today;
?>

</body>
</html>




20/02/2021



03.  

<!DOCTYPE html>
<html>
  <head>
    <title>The &lt;div&gt; Tag</title>
  </head>
  <body>
    <h1> The &lt;div&gt; Tag </h1>
    <div style="background-color:#8ebf42">
      <p>We use the &lt;div&gt; tag to group two paragraphs for applying a background to the text, and to add color to this
        <span style="color:#1c87c9">word</span> we place it within &lt;span&gt; tag.</p>
      <p> Pay attention, that the &lt;div&gt; tag is a block-level element, so a line break is placed before and after
        it.</p>
    </div>
  </body>
</html>

The <div> Tag
We use the <div> tag to group two paragraphs for applying a background to the text, and to add color to this word we place it within <span> tag.
Pay attention, that the <div> tag is a block-level element, so a line break is placed before and after it.





04. HTML Text Formatting

<!DOCTYPE html>
<html>
<body>

<p><b>This text is bold</b></p>
<p><i>This text is italic</i></p>
<p>This is<sub> subscript</sub> and <sup>superscript</sup></p>

</body>
</html>


This text is bold
This text is italic
This is subscript and superscript





05. HTML <cite> for Work Title

https://www.w3schools.com/html/html_quotation_elements.asp


<!DOCTYPE html>
<html>
<body>

<p>The HTML cite element defines the title of a work.</p>
<p>Browsers usually display cite elements in italic.</p>

<img src="img_the_scream.jpg" width="220" height="277" alt="The Scream">
<p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>

</body>
</html>


The HTML cite element defines the title of a work.
Browsers usually display cite elements in italic.

The Scream by Edvard Munch. Painted in 1893.






06. Border Color

https://www.w3schools.com/html/html_colors.asp

<!DOCTYPE html>
<html>
<body>

<h1 style="border: 2px solid Tomato;">Hello World</h1>

<h1 style="border: 2px solid DodgerBlue;">Hello World</h1>

<h1 style="border: 2px solid Violet;">Hello World</h1>

</body>
</html>

Hello World
Hello World
Hello World





07. Link Buttons

https://www.w3schools.com/html/html_links_colors.asp

<!DOCTYPE html>
<html>
<head>
<style>
a:link, a:visited {
  background-color: #f44336;
  color: white;
  padding: 15px 25px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
}

a:hover, a:active {
  background-color: red;
}
</style>
</head>
<body>

<h2>Link Button</h2>
<p>A link styled as a button:</p>
<a href="default.asp" target="_blank">This is a link</a>

</body>
</html>

Link Button
A link styled as a button:
This is a link




08. Animated Images

https://www.w3schools.com/html/html_images.asp

<!DOCTYPE html>
<html>
<body>

<h2>Animated Images</h2>

<p>HTML allows moving images:</p>

<img src="programming.gif" alt="Computer man" style="width:48px;height:48px;">

</body>
</html>

Animated Images
HTML allows moving images:




09. HTML head Elements

https://www.w3schools.com/html/html_head.asp

<!DOCTYPE html>
<html>
<head>
  <base href="https://www.w3schools.com/" target="_blank">
</head>
<body>

<h1>The base element</h1>

<p><img src="images/stickman.gif" width="24" height="39" alt="Stickman"> - Notice that we have only specified a relative address for the image. Since we have specified a base URL in the head section, the browser will look for the image at "https://www.w3schools.com/images/stickman.gif".</p>

<p><a href="tags/tag_base.asp">HTML base tag</a> - Notice that the link opens in a new window, even if it has no target="_blank" attribute. This is because the target attribute of the base element is set to "_blank".</p>

</body>
</html>

The base element
 - Notice that we have only specified a relative address for the image. Since we have specified a base URL in the head section, the browser will look for the image at "https://www.w3schools.com/images/stickman.gif".
HTML base tag - Notice that the link opens in a new window, even if it has no target="_blank" attribute. This is because the target attribute of the base element is set to "_blank".



10. HTML emojis

https://www.w3schools.com/html/html_emojis.asp

<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
</head>
<body>

<h1>Sized Emojis</h1>

<p style="font-size:48px">
&#128512; &#128516; &#128525; &#128151;
</p>

</body>
</html>
Sized Emojis
😀 😄 😍 💗


8 sept. 2022

 01. 

https://www.tutorialrepublic.com/codelab.php?topic=css&file=margin

<!DOCTYPE html>
<html lang="en">
<head>  <meta charset="utf-8">
<title>CSS Margin for Individual Sides</title>
<style>    h1 {        margin-top: 50px;
        margin-bottom: 100px;
        background: yellow;
    }   p {  margin-left: 75px;
        margin-right: 75px;
        background: yellow;
    } </style>
</head>
<body>
    <h1>This is a heading</h1>
    <p>This is a simple paragraph of text.</p>
    <p><strong>Note:</strong> Play with the margin property value to see how it works.</p>
</body>
</html>


This is a heading
This is a simple paragraph of text.
Note: Play with the margin property value to see how it works.




 02. 

fr.khanacademy.org/computing/computer-programming/html-css/css-layout-properties/pt/css-box-model

<!doctype html>
<html>
<head>
    <title>CSS box model</title>
    <meta charset="utf-8">
    <style>
        .lovey-dovey {
            color: red;
        }
                #official-info {
            background: rgb(230, 230, 230);
            width: 70%;
            height: 180px;
            overflow-y: auto;
            overflow-x: hidden;
        }
              #cute-cat {
            width: 120px;
        }
    </style>
</head>
<body>
    
    <h3>The Box Model</h3>
    <img src="https://www.kasandbox.org/programming-images/misc/boxmodel.png" width="380">
        <h1>All About Cats</h1>
    <h3>Why I <span class="lovey-dovey">Love</span> Cats</h3>
    <ul>
        <li>Furry
        <li>Cute
        <li>Evil
    </ul>
    <div id="official-info"><h3>Official Info on Cats</h3>
    <p><img id="cute-cat" src="https://www.kasandbox.org/programming-images/animals/cat.png"> The cat (Felis catus),.</p>
    <p>.</p>
    <p>Despite.</p>
    <p>Cats.</p>
    </div>
        Read more on <a href="http://en.wikipedia.org/wiki/Cat">Wikipedia</a>.
</body>
</html>
All About Cats
Why I Love Cats
Furry
Cute
Evil
Official Info on Cats
 The cat (Felis catus), a  Earth.
Cat.
Despite 
Cats.
Read more on Wikipedia.

  


 03. 

fr.khanacademy.org/computing/computer-programming/html-css/css-layout-properties/pt/css-box-model

<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>CSS position</title>
        <style>
        body {
            font-family: fantasy;
            color: rgb(199, 177, 14);
        }
        
        #landscape {
            width: 250px;
        }
        </style>
    </head>
    <body>

    <h1>Dance Party</h1>

    <img src="https://www.kasandbox.org/programming-images/landscapes/fields-of-grain.png" id="landscape">
    <img src="https://www.kasandbox.org/programming-images/avatars/Hopper-jumping.gif" id="hopper">
    <img src="https://www.kasandbox.org/programming-images/creatures/Winston.png" id="winston">
    
    <div id="song">
    <h3>Jamming to "Fields of Gold" by Sting</h3>
    <p>You'll remember me when the west wind moves<br>
Upon the fields of barley<br>
You'll forget the sun in his jealous sky<br>
As we walk in fields of gold
    </p>
    
    <p>So she took her love<br>
For to gaze awhile<br>
Upon the fields of barley<br>
In his arms she fell as her hair came down<br>
Among the fields of gold</p>

    <p>Will you stay with me, will you be my love<br>
Among the fields of barley<br>
We'll forget the sun in his jealous sky<br>
As we lie in fields of gold</p>
    </div>
    
    </body>
</html>

Dance Party
  
Jamming to "Fields of Gold" by Sting
You'll remember me when the west wind moves




 04. text decoration
https://www.tutorialspoint.com/css/css_text.htm
<html>
   <head>
   </head>
   <body>
      <p style = "text-decoration:underline;">
         This will be underlined
      </p>
      
      <p style = "text-decoration:line-through;">
         This will be striked through.
      </p>
      
      <p style = "text-decoration:overline;">
         This will have a over line.
      </p>
      
      <p style = "text-decoration:blink;">
         This text will have blinking effect
      </p>
   </body>
</html>


This will be underlined
This will be striked through.
This will have a over line.
This text will have blinking effect



 05. borders

https://www.tutorialspoint.com/css/css_borders.htm

<html>
   <head>
      <style type = "text/css">
         p.example1 {
            border:1px solid;
            border-bottom-color:#009900; /* Green */
            border-top-color:#FF0000;    /* Red */
            border-left-color:#330000;   /* Black */
            border-right-color:#0000CC;  /* Blue */
         }
         p.example2 {
            border:1px solid;
            border-color:#009900;        /* Green */
         }
      </style>
   </head>

   <body>
      <p class = "example1">
         This example is showing all borders in different colors.
      </p>
      
      <p class = "example2">
         This example is showing all borders in green color only.
      </p>
   </body>
</html>


This example is showing all borders in different colors.
This example is showing all borders in green color only.



 06. Colors

https://www.tutorialspoint.com/css/css3_color.htm

<html>
   <head>
      <style>
         #m1 {background-color:rgb(255,0,0);opacity:0.6;} 
         #m2 {background-color:rgb(0,255,0);opacity:0.6;} 
         #m3 {background-color:rgb(0,0,255);opacity:0.6;}
      </style>
   </head>
   <body>
      <p>HSLA colors:</p>
      <p id = "m1">Red</p>
      <p id = "m2">Green</p>
      <p id = "m3">Blue</p>
   </body>
</html>

HSLA colors:
Red
Green
Blue





 07.  2d transform

https://www.tutorialspoint.com/css/css3_2d_transform.htm

<html>
   <head>
       <style>
         div {
            width: 300px;
            height: 100px;
            background-color: pink;
            border: 1px solid black;
         }
         div#myDiv {
            /* IE 9 */
            -ms-transform: rotate(20deg);
                        /* Safari */
            -webkit-transform: rotate(20deg);
                        /* Standard syntax */
            transform: rotate(20deg);
         }
      </style>
        </head>
   <body>
      <div>
         Tutorials point.com.
      </div>
          <div id = "myDiv">
         Tutorials point.com
      </div>
   </body>
</html>


Tutorials point.com.
Tutorials point.com
















