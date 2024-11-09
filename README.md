# Surface-brightness-of-NGC-7793

   ********************************************CONTEXT********************************************

This project was done during the 45th edition of ISYA (International School For Young Astronomers). 
We had to plot the surface brightness of a galaxy called NGC 7793 that we asked purposfully to observe using the Las Cumbres observatory. 
The request was successfully accepted, so as the project.

   *******************************************THE CODE******************************************* 

For the code, we used famous libraries like numpy, photutils, astropy, ... 

We used photutils to trace out ellipses of constant luminosity called isophotes. These isophotes count the number of photons colliding the CCD camera on a specific pixel.

Multiple ellipses are generated using a method provided by photutils providing in addition to that error bars that helps you to decide on whether or not the model is good enough.

Provided that we have multiple isophotes traced out we can use them to trace out the surface brightness of a galaxy going from the center of the galaxy to the far end. 

