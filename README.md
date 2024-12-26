# Computer Vision Projects - Fall 2024

This repository contains my solutions for the two computer vision projects completed as part of the **CS GY 6643 - Computer Vision** course at NYU Tandon. Each project explored foundational techniques in computer vision, implemented from scratch without the use of pre-built libraries for the core algorithms.

## Project 1: Foundations of Image Processing

1. **Histogram Equalization**  
   - Implemented functions for computing the Probability Density Function (PDF) and Cumulative Distribution Function (CDF) for image histograms.
   - Enhanced image contrast by applying histogram equalization and analyzed its effects on image clarity and intensity.

2. **Image Thresholding**  
   - Applied Otsu's thresholding method to segment images and visualized inter-class variance.
   - Explored the Niblack thresholding algorithm with different filter shapes to enhance cell boundaries in Transmission Electron Microscopy (TEM) images.
   - Compared the effectiveness of Otsu’s and Niblack thresholding methods.

3. **Template Matching**  
   - Used cross-correlation to locate specific objects within a cluttered scene.
   - Detected peaks in correlation maps and marked the identified locations on the original image.
   - Analyzed results and discussed potential sources of false peaks.

4. **Creative Section**  
   - Developed an optimized approach for object detection to outperform standard cross-correlation in terms of execution time and efficiency.

---

## Project 2: Advanced Vision Techniques

1. **Image Transformation and Stitching**  
   - Aligned and stitched partial images to reconstruct a complete image resembling an A4 sheet.
   - Compared manual feature selection and automated feature descriptors (e.g., SIFT, ORB) for image alignment and blending.

2. **Hough Transform**  
   - Detected straight lines to simulate runway detection for spacecraft landing.
   - Implemented circular Hough Transform to identify circular landing pads, mimicking autonomous spacecraft navigation.

3. **Image Segmentation**  
   - Employed Mean Shift Segmentation and Normalized Graph Cut Segmentation to isolate stop signs in challenging scenarios.
   - Discussed the strengths and weaknesses of both approaches in the context of road sign detection.

4. **Creative Section**  
   - Designed a custom segmentation algorithm leveraging classical techniques.
   - Evaluated performance using Intersection over Union (IoU) as a metric and compared results with existing approaches.

---

Each project includes:
- **Colab Notebooks**: Implementation details and step-by-step analysis.
- **Reports**: Comprehensive explanations, results, and discussions.

Explore the repository for detailed implementations and insights into these computer vision techniques. Contributions and feedback are welcome!
