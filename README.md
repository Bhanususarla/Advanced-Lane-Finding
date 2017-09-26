# Advanced-Lane-Finding

In this project, the goal is to write a software pipeline to identify the lane boundaries in a video from a front-facing camera on a car. This can be achieved by the following steps:
1. Compute the camera calibration matrix and distortion coefficients given a set of chessboard images. 
2. Apply a distortion correction to raw images. 
3. Use color transforms, gradients, etc., to create a thresholded binary image. 
4. Apply a perspective transform to rectify binary image ("birds-eye view"). 
5. Detect lane pixels and fit to find the lane boundary. 
6. Determine the curvature of the lane and vehicle position with respect to center. 
7. Warp the detected lane boundaries back onto the original image. 
8. Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position.

See pdf for full report
