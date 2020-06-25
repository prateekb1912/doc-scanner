[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

# Mobile Document Scanner with Python and OpenCV
So, I finally completed my first CV project : A Mobile Document Scanner 
## How do I Scan my Documents?
Easy, just fork this repo into your local machine and then type the following command in the repo directory :
<pre>
<code>
python3 scan.py --image "your-image-file-name-here"
</code>
</pre>

## Okay, but how does it works?
The program converts the document image into a scanned file in three steps : <br>
<ol>
  <li><b>Edge Detection</b></li><br>
<img src='screenshots/ss1.png' height=450 width=450 alt='edged_image'>
<p>You can see the original image on the left and the edge detected image on the right.</p>
  <li><b>Contour Drawing</b></li><br>
<img src='screenshots/ss2.png' height=450 width=450 alt='edged_image'>
<p>See that blue rectangular border around the receipt? That's what a drawn contour is.</p>
  <li><b>Perspective Transformation</b></li><br>
<img src='screenshots/ss1.png' height=450 width=450 alt='edged_image'>
<p>And Voila!, just how we wanted the scanned receipt.</p>
