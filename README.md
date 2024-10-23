# BarnacleVision
Using computer vision to count barnacles in an image. 

Currently labelling training data. 

Work in progress. 

I have tried several methods but barnacles are too complex. I've tried converting to grayscale, applying gaussiun blur, using edge detection, finding contours, filtering out contours, and then counting the number of barnacles based on contours. This works for more homogenous objects such as pebbles or marbles, but barnacles exhibit too much variation. I tried leveraging transfer learning with the VGG16 architecture, using images with associated total counts, but this still had about 40% error. 

Now I am trying to manually label all the barnacles and proceed from there. 
