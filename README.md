# BarnacleVision
Using computer vision to count barnacles in an image. 

Currently labelling training data. 

Work in progress. 

I have tried several methods but barnacles are too complex. I've tried converting to grayscale, applying gaussiun blur, using edge detection, finding contours, filtering out contours, and then counting the number of barnacles based on contours. This works for more homogenous objects such as pebbles or marbles, but barnacles exhibit too much variation. I tried leveraging transfer learning with the VGG16 architecture, using images with associated total counts, but this still had about 40% error. 

Now I am trying to manually label all the barnacles and proceed from there. 


![image](https://github.com/user-attachments/assets/1c0df695-a2b0-4b54-9e21-5134e6023ba6)

![image](https://github.com/user-attachments/assets/b01580f8-656f-4280-975e-7524cded2ad7)

![image](https://github.com/user-attachments/assets/1935ae2b-8692-4f17-9595-38e8d65f0a45)

* Adjusting the threshold doesn't seem effective, likely because of too much variation in image (from shadows).

![image](https://github.com/user-attachments/assets/fa5bdf99-9c68-4ee6-83e7-8a50c023486a)

![image](https://github.com/user-attachments/assets/455270e8-9588-48a8-be5e-d4c50e2abd5e)

![image](https://github.com/user-attachments/assets/247a9543-55a6-4715-9c50-e784ed926f27)


![image](https://github.com/user-attachments/assets/e7651a9e-664b-4b10-924b-0638392da5ea)

![image](https://github.com/user-attachments/assets/9fa6445f-4d63-41b8-8281-190e3ae1e816)

