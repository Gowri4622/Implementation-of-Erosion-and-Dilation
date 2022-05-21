# Implementation-of-Erosion-and-Dilation
## Aim
To implement Erosion and Dilation using Python and OpenCV.
## Software Required
1. Anaconda - Python 3.7
2. OpenCV
## Algorithm:
### Step1:
<br>


### Step2:
<br>

### Step3:
<br>

### Step4:
<br>

### Step5:
<br>

 
## Program:

``` Python
# Import the necessary packages
import cv2
import numpy as np
import matplotlib.pyplot as plt


# Create the Text using cv2.putText
img=np.zeros((100,200), dtype='uint8')
font=cv2.FONT_HERSHEY_SIMPLEX
cv2.putText(img,'Gowri M',(5,70),font,2,(255),5,cv2.LINE_AA)


# Create the structuring element



# Erode the image




# Dilate the image





```
## Output:

### Display the input Image
![Screenshot_666](https://user-images.githubusercontent.com/75235455/169638704-de793615-e394-4ca3-8d54-26197d7fee3d.png)
<br>
<br>
<br>
<br>
<br>
<br>

### Display the Eroded Image
![Screenshot_664](https://user-images.githubusercontent.com/75235455/169638701-ea142883-6d0c-4c4a-a04f-765e904463a2.png)
<br>
<br>
<br>
<br>
<br>
<br>

### Display the Dilated Image
![Screenshot_665](https://user-images.githubusercontent.com/75235455/169638694-db8d8c4a-c8ef-4ccf-803f-83aa29104cac.png)
<br>
<br>
<br>
<br>
<br>
<br>

## Result
Thus the generated text image is eroded and dilated using python and OpenCV.
