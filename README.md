## Overview
This repository contains a Python project that utilizes computer vision techniques to detect tampering in PAN (Permanent Account Number) cards. The project leverages image processing, thresholding, and difference calculations to identify any alterations or modifications in the provided PAN card images.

 ## Features
Image Thresholding: Apply thresholding techniques to convert images into binary representations, enhancing the visibility of differences between the original and tampered images.

 ## Structural Similarity Index (SSIM): Calculate the SSIM score to quantify the structural similarity between the original and tampered images.

- Contour Detection: Detect contours of differences in thresholded images to outline areas of tampering.

- Bounding Rectangles: Draw bounding rectangles around detected differences, providing a visual highlight of tampered regions.

- User-Friendly Visualization: Display original, tampered, and difference images using the Pillow and matplotlib libraries.

 ## How to Use
Clone this repository to your local machine.
Make sure you have the required Python libraries installed (cv2, numpy, skimage.metrics, imutils, PIL, matplotlib).
Run the provided script to perform image thresholding, SSIM calculation, contour detection, and visualization of differences.
