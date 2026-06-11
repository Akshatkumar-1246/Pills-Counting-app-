# Pills-Counting-app-

## Problem-
Counting Number of pills in Industry and Medical Feild is very important work 
It is time taking and high error process 
so i develope a system which count number of pills in the given image 

## Overview
This project detects and counts pills in an image using OpenCV image processing techniques. The image is preprocessed, segmented using canny edge detection, and analyzed with contour detection to determine the total number of pills.

## Features
- Image preprocessing with Gaussian Blur
- Edge detection using canny edge detection 
- Contour detection and filtering
- Automatic pill counting
- Visualization of detected pills

## Technologies Used
- Python
- OpenCV
- NumPy
- Matplotlib

## Workflow
1. Load the image.
2. Convert to grayscale.
3. Apply Gaussian Blur to reduce noise.
4. Perform Edge detection .
5. Detect contours of individual pills.
6. Filter contours based on area.
7. Count valid contours and display the result.

## Output
The program displays:
- The processed image with detected pill boundaries.
- Total number of pills present in the image.

## Applications
- Pharmaceutical inventory management
- Automated medicine packaging systems
- Quality inspection in pharmaceutical industries

## Future Improvements
- Counting overlapping pills using Watershed Segmentation.
- Real-time pill counting from a camera feed.
- Classification of pills based on shape, size, or color.
