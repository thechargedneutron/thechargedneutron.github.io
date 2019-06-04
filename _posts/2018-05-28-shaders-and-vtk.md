---
title: "Interesting World of Shaders and VTK"
layout: post
date: 2018-05-28 22:44
image: /assets/images/markdown.jpg
headerImage: false
tag:
- GSoC
- PSF
- Open Source
- dipy
category: blog
author: kumarashutosh
description: GSoC Mode On!!
---

Hey folks,
The last two weeks were full of fun. Sitting near my screen exploring various shaders was fun. With the help of Elef and Ranveer, I could do a lot of different examples and all this helped me build some really cool visualization examples (At least I was amazed :P ).
So let me walk you through few things I achieved over the past two weeks.

- Displaying Frame-Rate of vtk Renderer
The example renders ten small unit radii spheres and displays the number of times the screen is rendered per second.  It is calculated by finding the inverse of the last rendering time (in seconds of course). And we obtain last rendering time using a callback function GetLastRenderTimeInSeconds. As the name suggests, this function returns the time delay between last rendering time and the present rendering time.
A small demo of the work is available here:

The documented code is available here.

- Taking user inputs to Shaders using SetUniformf
This task was aimed at understanding how to use user input to set shader properties. I came up with a code which takes as an input our choice for RGB values and returns a sphere of that color.
SetUniformf is a very important tool which magically acts as an interface between the OpenGL world of shaders and our Python world. As we move on to more complicated tasks, this function will be increasingly useful for sure.
A small demo of the code is available here:

The documented code can be found here.

- Constructing Sphere using fundamental blocks - Vertices and Faces
It was very interesting to know how any 3D shape is rendered using triangles as the fundamental block. I tried to visualize the same in a more general way. The rendered shape can be changed to ellipsoid very easily. I am currently working on including a slider which changes the dimension of the sphere as per the slider input. The sphere looks deformed (intentionally) to emphasize the use of triangles to form the sphere. I have used as less as 24 triangles to get a sphere.
The sphere looks like this:

The documented code can be found here.

- Extending the to-be-added sphere function
Elef is working on a Pull Request to add sphere function. The sphere would help to produce 3D Glyphs. The purpose of my work is to allow for additional parameters -vertices and faces, which would act as an alternative to the traditional center and radii thing. The Pull Request is under review and can be seen here.

It is really fun working with my mentors and the awesome community at dipy. I strive to learn new things and will try more such interesting stuff as we proceed. I'm loving GSoC :) . Looking forward to more fun this summer.

thechargedneutron