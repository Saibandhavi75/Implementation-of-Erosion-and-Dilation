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
import cv2
import numpy
NameImage = numpy.zeros((100,1000),dtype='uint8')
font = cv2.FONT_ITALIC
cv2.putText(NameImage,'Sai Bandhavi',(50,70),font,2,(255),5,cv2.LINE_4)
cv2.imshow("Name Image",NameImage)
kernel1 = cv2.getStructuringElement(cv2.MORPH_CROSS,(7,7))
erodeImage = cv2.erode(NameImage,kernel1)
dilationImage = cv2.dilate(NameImage,kernel1)
cv2.imshow("Erode Image",erodeImage)
cv2.imshow("Dilated Image",dilationImage)
cv2.waitKey(0)

cv2.destroyAllWindows()


```
## Output:

### Display the input Image
![output](?raw=true)

### Display the Eroded Image
![output](?raw=true)

### Display the Dilated Image
![output](?raw=true)

## Result
Thus the generated text image is eroded and dilated using python and OpenCV.
