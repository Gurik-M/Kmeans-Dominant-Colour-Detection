# Kmeans Dominant Colour Detection
A k-means clustering computer vision algorithm for detecting the dominant color in an image.


## Overview
K-means clustering is a technique that groups "n" observations into "k" distinct clusters. This project uses the SciKit-learn K-means library to use k-means clustering as a method of computing the dominant colour in an inputted image. The RGB (red, green, blue) values of pixels in the image are taken and assigned to a nearest cluster. Each of those clusters represents a different colour and the largest cluster represents the most dominant colour. The center of each cluster (also known as the centroid) is located by averaging the distances of all the associated points using the following distance equation where the x and y  values are the coordinates of the points: d = sqrt{(x2 - x1^)2 + (y2 - y1)^2}
 The centroid of each cluster then gives us the RGB values of the most dominant color in the image.
 
 ## Graphical Representation
 The output of the K-means clustering algorithm can also be expressed graphically. Take the following image for example:
 ![Example Kmeans Image](https://github.com/Gurik-M/Kmeans-Dominant-Colour-Detection/blob/master/Images/example_kmeans_image.png)

After running the K-means algorithm, we find out that the RGB values of it's most dominant colour are: [128, 170, 8] and by using the Matplotlib library, we can graphically represnt the distinct clusters:
![Example Kmeans Image](https://github.com/Gurik-M/Kmeans-Dominant-Colour-Detection/blob/master/Images/example_kmeans_graph.png)



