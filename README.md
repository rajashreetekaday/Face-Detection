# Face-Detection
Built a model using the pre-trained HAAR Cascade classifier in OpenCV to detect faces in an image.
### HAAR Cascade
It is an Object Detection Algorithm used to identify faces in an image. The algorithm uses edge or line detection features proposed by Viola and Jones (HAAR Feautures)
The algorithm is given a lot of positive images consisting of faces, and a lot of negative images not consisting of any face to train on them. 

### HAAR-Features
These features on the image makes it easy to find out the edges or the lines in the image, or to pick areas where there is a sudden change in the intensities of the pixels.

![](https://i.imgur.com/v2afj6r.png)

The haar feature continuously traverses from the top left of the image to the bottom right to search for the particular feature. 
An **Integral Image** is calculated from the Original Image in such a way that each pixel in this is the sum of all the pixels lying in its left and above in the Original Image. It was introduced to reduce the time complexity
 
### Attentional Cascade. 
Not all the features need to run on each and every window. If a feature fails on a particular window, then we can say that the facial features are not present there. Hence, we can move to the next windows where there can be facial features present.

## RESULTS
![](https://i.imgur.com/FclaMNR.png)

![](https://i.imgur.com/B68C8pS.png)

![](https://i.imgur.com/NYfPOfO.png)

![](https://i.imgur.com/bVg6L30.png)


