---
layout: page
title: Portfolio
permalink: /portfolio/
---
NOTE: Will post some of my more software-related projects with github links soon (7/31/2015)

## NASA/CUA PADS Project
<div style="text-align:center" markdown="1">
![alt text][pads_outside]
</div>

Between fall 2013 and fall 2014, I was fortunate enough to be both a project manager and student engineer 
for a team from my alma mater to create a high altitude balloon payload. In conjunction with NASA Goddard 
Space Flight center and CUA, our mission was to construct an attitude determination system using off-the-shelf products. 

We were also selected to test if a plurality of lower end MEMS gyros could "vote" together 
to form a reading which featured reduced noise and compare results with other attitude determination devices. 
The result was a full working payload that successfully launched in August 2014 at the Columbia Scientific Balloon 
Facility in Fort Sumner, NM. 

[Here is a link to view the flight info](http://towerfts.csbf.nasa.gov/Maps/ConvGps651N.htm)

The payload included: gyros, clinometers, magnetometers, a DSLR camera, a raspberry pi, 
and enclosures (one of which was a cylindrical pressure vessel).	


## Lock Unlocking Operator (LUO)

<div style="text-align:center" markdown="1">
<video width="320" height="240" controls>
<source src="../assets/LUO_demo.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
</div>


This was a final project for my applied mechatronics course
at CUA, alongside two other engineering students.
The LUO is an arduino mechatronics project which could unlock
a master lock. Using a stepper motor, servo motor, and an arduino
uno, the LUO using the serial monitor on the Arduino IDE
as a means of taking user input. The user can input possible
combinations for the mechanism input into the lock. After the
last number is entered, the servo motor would actuate and
attempt to pull the shackle to open it. 


## LilPlane Mechanical Engineering Capstone Project

<div style="text-align:center" markdown="1">
![alt text][plane]
</div>

LilPlane is a gaint scale rc airplane built for Catholic University's bid into the Society for Aeronautical Engineers
AeroDesign competition held in Marietta, GA. The goal was to lift as much as possible given volume and power restrictions. 

All components were the result of rigorous testing and simulations via MATLAB and XFLR5 computational fluid dynamics software. 
This plane featured a high wing dihedral, a tail dragger configuration, and an electric motor that was to output no more than 1000 watts.
The poster [linked here][poster] was awarded the departmental award at CUA.


<!--vars for assets go here-->
[pads_outside]: ../assets/pads_outside.jpg "PADS payload"
[poster]: ../assets/poster.jpg "capstone poster"
[plane]: ../assets/lil_plane.jpg "lil plane"
