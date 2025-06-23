# Lane Detection 

This project implements a lane detection algorithm using computer vision techniques. It detects lanes in images and highlights them, providing a visual representation of the detected lanes on the road.

## Overview

The project performs the following steps:

1. **Image Loading:** The input image is loaded using OpenCV.

2. **Edge Detection:** Edge detection is applied to the grayscale image using the Canny edge detector.

3. **Region of Interest (ROI) Selection:** A specific region of interest is defined in the image, focusing on the area where lanes are expected.

4. **Hough Transform:** The Hough transform is applied to detect lines in the region of interest.

5. **Visualization:** Detected lines are overlaid on the original image to highlight the lanes.


## Prerequisites

- OpenCV
- Matplotlib
- NumPy

## Results

1. **Original Image**

   
   ![Original Image](results/original.png)

2. **Detected Edges Image**

   
   ![Detected Edges Image](results/detected_edges.png)

3. **ROI Image**

   
   ![ROI Image](results/roi_image.png)

4. **Detected Lanes Image**

   
   ![Detected Lanes Image](results/detected_lanes.png)


## Parameters

Adjustable parameters in the code include:

- Canny edge detection thresholds.
- Region of interest vertices and dimensions.
- Hough transform parameters.

Feel free to experiment with these parameters for different images and scenarios.

## Maintainer

**Sai Sandeep Kethiboina**
AI and Machine Learning Engineer

Sai is an AI/ML Engineer and Data Scientist with over 5 years of experience designing, developing, and deploying scalable Artificial Intelligence, Machine Learning, and Deep Learning solutions. This project reflects his ongoing work in computer vision and image processing.

- **GitHub:** [GitHub Profile]
- **LinkedIn:** [LinkedIn Profile]
- **Email:** [Email Address]