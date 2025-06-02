Convert to Grayscale: Convert the input image to grayscale, as this is the first step towards creating a black and white sketch. 
Invert Grayscale Image: Invert the grayscale image. This is done to highlight the edges, making them more prominent in the sketch. 
Apply Gaussian Blur: Apply a Gaussian blur to the inverted grayscale image. This step reduces noise and smooths out the edges, preparing the image for edge detection. The radius of the Gaussian blur can be adjusted to control the appearance of the sketch lines. 
Invert Blurred Image: Invert the blurred image to get the final sketch lines. 

#Step - 1 - Load Libraries and Image
#Step - 2 - Convert Image into Gray Scale
#Step - 3 - Inverted Gray Scale Image.
#Step - 4 - Apply Image Smooting For Shading effect
#Step - 5 - Invert Blur Image and Apply division between gray and invert_blur.
