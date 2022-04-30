# Basic-Image-processing
A program to read, and show an image. Also to plot histogram for the image and apply mean thresholding

The code includes reading and displaying an image using OpenCV and Matplotlib.

Next, we plot a histogram for the intensities of the colors in the image. The histogram is plotted for the color (RGB) image as well as the black-and-white image.

The image is then converted into black and white and then different forms of median thresholding (binary, binary_inv, trunc, tozero, tozero_inv) have been applied on the entire image.

Next, we calculate the median pixel for each row and apply median thresholding for each of the row by assigning all values less than the median value as 0 and all values greater than median value as 255.

We apply median based thresholding in a similar way for all columns also
