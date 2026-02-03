

 Task 02: Image Segmentation and Object Counting

1. Objectives

· To implement Otsu’s automatic thresholding for converting grayscale images to binary.
· To apply morphological opening to remove small noise and refine object shapes.
· To perform Connected Component Labeling (CCL) for identifying and counting distinct objects.
· To visualize and analyze the results by comparing original, binary, and labeled images.

2. Scope

· Input: A single grayscale image (e.g., 1.jpg or 2.jpg).
· Processing Steps:
  · Image binarization using Otsu’s method.
  · Noise removal via morphological operations.
  · Object detection and counting using CCL.
· Output: Processed images and a count of detected objects.

3. Methodology

1. Image Reading: Load the grayscale image using OpenCV.
2. Thresholding: Apply Otsu’s method to create a binary image.
3. Morphological Cleaning: Use a kernel to perform opening (erosion + dilation).
4. Connected Component Labeling: Label each object with a unique ID and count them.
5. Visualization: Plot the original, binary, and labeled images side-by-side.

4. Expected Outcomes

· A binary image with objects clearly separated from the background.
· A noise-reduced version of the binary image.
· A labeled image where each object is distinctly colored.
· A printed count of detected objects in the image.

5. Tools & Libraries

· Python with OpenCV, NumPy, and Matplotlib.
· Jupyter Notebook for interactive execution and visualization.

6. Significance

· Demonstrates fundamental image processing techniques.
· Provides a pipeline for automated object detection and counting.
· Applicable in fields like industrial inspection, medical imaging, and document analysis.

---
