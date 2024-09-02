# Road-Lane-Detection
https://github.com/user-attachments/assets/b97b9fb1-27da-4a4b-a733-3f461a98e52e

This project demonstrates lane detection using OpenCV, incorporating improvements based on the generated results. The goal remains to identify and visualize the lane lines within a given road video.

## Key Features

- Image Preprocessing: Converts the input image to grayscale and applies Gaussian blurring to reduce noise.
- Edge Detection: Uses the Canny edge detection algorithm to identify potential edge points within the image.
- Region of Interest (ROI): Defines a specific region of the image to focus on, ensuring that only relevant areas are considered for lane detection.
- Hough Transform: Applies the Hough Transform to detect lines within the specified ROI.
- Line Filtering: Filters the detected lines based on their slope and orientation to identify the most likely lane lines.
- Line Averaging: Averages the detected lane lines to reduce noise and improve accuracy.
- Line Extrapolation: Extrapolates the lane lines to predict their continuation beyond the visible portion of the image.
- Line Drawing: Draw the detected lane lines onto the original video for visualization.


The project assumes that the input image contains clear lane markings and is taken from a road environment.
The parameters for the Canny edge detection, Hough Transform, and other components can be adjusted to fine-tune the performance.
