# Digital Image Processing Assignments

This repository contains weekly assignments of Comp 403 course in Istanbul Bilgi University.

Please read the license file. I do NOT take any responsibility in case of plagiarism. It's only educational purpose.

## Assignment 01: Quantization

Your input image is the "Lena.jpg" picture.

* What is the size of the picture?
* What type of image is it?
* Your task is to read the original image and to modify it using a 3-bit quantization bar. Your MATLAB
code will show the image before and after the quantization process.

Click [here](https://github.com/mdegis/Image-Processing/blob/master/Quantization.m) to see my solution.

Example Output:

![ScreenShot](https://raw.github.com/mdegis/Image-Processing/master/outputs/QuantizationOUTPUT.png?token=1271373__eyJzY29wZSI6IlJhd0Jsb2I6bWRlZ2lzL0ltYWdlLVByb2Nlc3NpbmcvbWFzdGVyL291dHB1dHMvUXVhbnRpemF0aW9uT1VUUFVULnBuZyIsImV4cGlyZXMiOjEzODQzNzkxOTh9--758f8249f0edff83e05eb6f94d97f47ad00369f1)

## Assignment 02: BitPlane Slicing

A digital image is a matrix f(x,y)=greylevel, where the greylevel is the pixel’value, it is a digital numbers composed of bits. For example the intensity of each pixel in a 256-level gray-scale image is composed of 8-bits. Therefore an 8-bit image may be considered as being compose of eight 1-bit planes, with plane 1 containing the lowest-order bit, and plane 8 the highest orderer bit of all pixels in the image.

Your input image is the ”Lena.jpg” picture:

* Your task is to read the original image and to create the corresponding eight 1-bit planes
* Your MATLAB code will show the original image and all the eight 1-bit planes.

Click [here](https://github.com/mdegis/Image-Processing/blob/master/BitPlaneSlicing.m) to see my solution.

Example Output:

![ScreenShot](https://raw.github.com/mdegis/Image-Processing/master/outputs/BitPlaneSlicingOUTPUT.png?token=1271373__eyJzY29wZSI6IlJhd0Jsb2I6bWRlZ2lzL0ltYWdlLVByb2Nlc3NpbmcvbWFzdGVyL291dHB1dHMvQml0UGxhbmVTbGljaW5nT1VUUFVULnBuZyIsImV4cGlyZXMiOjEzODQzNzkyMTh9--ad3abfa5e5c5022b70fbd2593acbd9166ccc962d)