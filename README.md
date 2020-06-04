minimal p5 starter - Organised by Keir

ABOUT:
    This repository contains the minimal amount of code you need to start a P5.js sketch

NOTE:
You will need to be online for this code to work as the P5.js library needed for this code are downloaded (by the code) from an online server.

CONTAINED:
[ index.html ] - A html file which gets the needed p5.js library and displays the p5.js sketch
[ sketch.js ] - A javascript file which is where you write your p5.js code

INTRO TO P5 - Main Functions:
[ function setup() ] - the setup function runs once when you first start the program. It (normally) always includes the createCanvas() function which takes three parameters which are the width, height and the renderer. For example a canvas which is 400px by 300px would be written as createCanvas(400,300);

[ function draw() ] - the draw function attempts to run 60 times a second. This works similar to the way update/draw functions work in OpenFrameworks and Processing. 

INTO TO P5 - Regularly used functions:

rect(x,y,width,height) - displays rectangle
ellipse(x,y,width,height) - displays ellipse
line(x1,y1,x2,y2) - displays line

fill(colorValue) - fills shapes with a certain color
stroke(colorValue) - fills the line of shapes with a certain color
noFill() - removes the fill color (makes transparent)
noStroke() - removes stroke color (makes transparent)
