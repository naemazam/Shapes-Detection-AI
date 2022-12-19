# Shapes-Detection-AI

Shapes Detection OpenCV Python


The Shapes Detection OpenCV Python was developed using Python OpenCV , In this Shape Detection OpenCV Python project I am taking an image that contains shapes like triangle, square, rectangle, and circle. The image is then converted to grayscale using the cvtColor() function.

# What is OpenCV?
OpenCV (Open Source Computer Vision Library) is an open-source computer vision and machine learning software library. OpenCV was built to provide a common infrastructure for computer vision applications and to accelerate the use of machine perception in commercial products.

# Method
The Grayscaled image is then Thresholded using the THRESH_BINARY Method. The Thresholded image is then taken and contours are found on that image. The Contours obtained are then looped and the edges are counted using the approxPolyDP() function, which takes each contour. The edges of the Contour is then drawn on the image using drawContours() function.

# Run

To start executing Shapes Detection OpenCV Python, make sure that you have installed Python 3.9 and PyCharm in your computer.
