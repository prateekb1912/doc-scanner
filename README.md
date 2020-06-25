# Mobile Document Scanner with Python and OpenCV
If you too are boycotting all Chineses apps, you should know CamScanner is one of them. So, in order to give India it's own simple document scanner with some additional features,
I have come up with this document scanner made in Python with the help of OpenCV.

## How do I Scan my Documents?
Easy, just fork this repo into your local machine and then type the following command in the repo directory :
<pre>
<code>
python3 scan.py --image "your-image-file-name-here"
</code>
</pre>

## Okay, but how does it works?
The program converts the document image into a scanned file in three steps :
1. Edge Detection
<img src='screenshots/ss1.png' height=150 width=150 alt='edged_image'>
You can see the original image on the left and the edge detected image on the right.
2. Contour Drawing
3. Perspective Transformation
