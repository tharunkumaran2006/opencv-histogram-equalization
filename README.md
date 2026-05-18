# opencv-histogram-equalization

## AIM

To perform color image enhancement using histogram equalization in the HSV color space with OpenCV and improve the brightness and contrast of the image while preserving natural colors.

## TECHNOLOGIES USED
1.Python

2.OpenCV

3.NumPy

4.Matplotlib

## ALGORITHM
1.Import the required libraries.

2.Read the input color image parrot.jpg.

3.Display the original image and plot its BGR histogram.

4.Convert the image from BGR color space to HSV color space.

5.Split the HSV image into H, S, and V channels.

6.Apply histogram equalization on the V channel using cv2.equalizeHist().

7.Merge the H, S, and enhanced V channels.

8.Convert the enhanced HSV image back to BGR format.

9.Display the enhanced image and its histogram.

10.Show all outputs using a 2 × 2 grid layout.

## OUTPUT
### Original and Enhanced GrayScale Image and its Histogram
<img width="862" height="567" alt="image" src="https://github.com/user-attachments/assets/10ca05b0-2bfb-43e2-8bd0-09731dad4913" />

### Original Color Image
<img width="912" height="452" alt="image" src="https://github.com/user-attachments/assets/bbf302e7-75f8-4654-9749-df50af5deef3" />

### Histogram of Original Image (BGR channels)
<img width="903" height="589" alt="image" src="https://github.com/user-attachments/assets/5795caf9-e262-4f30-bf5c-033c555c6219" />

### Enhanced Color Image
<img width="909" height="442" alt="image" src="https://github.com/user-attachments/assets/a7ae2605-737c-4c45-94da-184778bcc998" />

### Histogram of Enhanced Image (BGR channels)
<img width="933" height="595" alt="image" src="https://github.com/user-attachments/assets/89bf6bf3-f19b-4900-b1a5-231a9c2c370b" />

The enhanced image appears brighter with improved contrast and better visibility of details.

## RESULT

Thus, histogram equalization in the HSV color space was successfully performed using OpenCV.
The brightness and contrast of the image were enhanced effectively by equalizing only the V channel while preserving the original color information.
