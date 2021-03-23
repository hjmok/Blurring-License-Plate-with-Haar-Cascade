# Blurring-License-Plate-with-Haar-Cascade

The purpose of this project is to show how to use OpenCV and License Plate (Russian) Haar Cascades to create a simple license plate detection and blurring program


## Haar Cascade
A pre-trained Russian license plate Haar Cascade was used for this plate detection model. The cascade was utilized by OpenCV.


## Detect and Blur Function
The purpose of the Detect and Blur function is take the image of the car and visualize the region of interest detected by the Haar cascade. Finally, it will blur out this region.
First a rectangle is animated around the detected plate by grabbing the x,y,width, and height coordinates from the cascade results. Then within this rectangle, a OpenCV's median blur is used to blur this region of interest. The function will return the modified image.

## Results
Please find the results in the following link: https://hjmok.github.io/josephmok_portfolio/#/license_plate 
