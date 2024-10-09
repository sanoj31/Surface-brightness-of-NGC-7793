# Surface-brightness-of-NGC-7793

   ********************************************CONTEXT********************************************

This project was done during the 45th edition of ISYA (International School For Young Astronomers). 
We had to plot the surface brightness of a galaxy called NGC 7793 that we asked purposfully to observe using the Las Cumbres observatory. 
The request was sucessful, so as the project.

   *******************************************THE CODE******************************************* 

For the code, we used famous libraries like numpy, photutils, astropy, ... 

We used photutils to trace out ellipses of constant luminosity called isophotes. These isophotes count the number of photons colliding the CCD camera on a specific pixel

Multiple ellipses are generated using a method provided by photutils providing additionnally error bars helping you to decide on whether or not the model is good enough. 
