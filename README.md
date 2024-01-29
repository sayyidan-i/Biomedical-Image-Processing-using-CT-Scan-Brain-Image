# Biomedical Image Processing Project

This project focuses on image processing techniques applied to CT-scan brain images. The goal is to explore and implement different image filtering methods to enhance the visual quality and extract meaningful information from the images.

## Project Overview

### 1. Average Filter
- **Implementation**: Utilizes an average filter for image smoothing.
- **Kernels Used**: 3x3 Average Filter, 3x3 Weighted Average Filter.
- **Metrics**: Computes Structural Similarity Index (SSIM) to evaluate the similarity between the original and filtered images.
- **Results**: Displays original, average-filtered, and weighted average-filtered images.

### 2. Median Filter
- **Implementation**: Applies a median filter to reduce noise in the images.
- **Kernel Size**: 3x3 Median Filter.
- **Metrics**: Calculates SSIM to assess the quality improvement.
- **Results**: Shows original and median-filtered images side by side.

## Dataset
The project utilizes CT-scan brain images for experimentation. The images are loaded from Google Drive for processing.

## Instructions
1. Connect to Google Drive to access the CT-scan brain images.
2. Execute the provided code in a Jupyter Notebook environment.
3. Observe the results and SSIM metrics for each filtering technique applied to different brain images.
4. Analyze and interpret the effectiveness of the image filtering methods.

Feel free to experiment with different filters, kernel sizes, and images to further explore the impact on image quality and feature extraction in biomedical image processing. If you have any questions or suggestions, feel free to reach out!
