# The-Smart-Board-Air-Canvas-Project
Computer vision project implemented with OpenCV

Ever wanted to draw your imagination by just waiving your finger in air. Here we will know how air canvas allows us to draw our imagination by just waiving our 
 finger in air.Here a coloured object at tip of finger is used as the marker.
+
+ The preffered language is python due to its  libraries and easy to use syntax but understanding the basics it can be implemented in by OpenCV language.Here Colour Detection and tracking is used in order to achieve the objective
+
+ # Algorithm
+1.Start reading the frames and convert the captured frames to HSV colour space.(Easy for colour detection)
+2.Prepare the canvas frame and put the respective ink buttons on it. 
+3. Adjust the trackbar values for finding the mask of coloured marker.
+4.Preprocess the mask with morphological operations.(Erotion and dilation)
+5.Detect the contours, find the center coordinates of largest contour and keep storing them in the array for successive frames .(Arrays for drawing points on canvas)
+6.Finally draw the points stored in array on the frames and canvas .

+Requirements:  opencv ,python3 and numpy.
