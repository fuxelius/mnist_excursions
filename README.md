# MNIST Excursions
**``By Hans-Henrik Fuxelius, 2023-05-29``

The objective here is, by dimensionality reduction, to take an image as input and reproduce an image as output by regression. It does not learn the features of the images, but the rules for transformation to desired output!

## MNIST image to image
The nn learns the transform for how to copy **any** image from input to output

![Input test image](img/plain_test_images_1378.png)

![Reproduced output image](img/plain_predictions_1378.png)

## MNIST image to mirrored image
The nn learns the transform for how to **mirror** **any** image from input to output

![Input test image](img/mirror_test_images_145.png)

![Mirrored output image](img/mirror_predictions_145.png)
