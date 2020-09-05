# Kmeans Dominant Colour Detection
A k-means clustering computer vision algorithm for detecting the dominant color in an image.


## Overview
K-means clustering is a technique that groups different observations into distinct clusters. The RGB (red, green, blue) values of pixels in the image are taken and assigned to a nearest cluster. Each of those clusters represents a different colour and the largest cluster represents the most dominant colour. The center of each cluster (also known as the centroid) is located by averaging the distances of all the associated points. This is carried out by using the following distance equation where the x and y  values are the coordinates of the points: d = sqrt{(x2 - x1^)2 + (y2 - y1)^2}
 
 The centroid of each cluster then gives us the RGB values of the most dominant color in the image.
 
 ## Graphical Representation
 



