# Cell Segmentation & Morphological Analysis
### This project focuses on segmenting and analyzing cells from two .tif microscopy images with varying cell shapes and densities.

#### Cell Segmentation:

1. Applies thresholding, morphological operations, distance transform, and the Watershed algorithm to separate overlapping cells.
2. Visualizes key stages: sure background, foreground, unknown regions, and final labels.

#### Feature Extraction:

1. Labels each segmented cell using cv2.connectedComponents.
2. Uses regionprops to extract:
   * Area
   * Perimeter
   * Major/Minor axis lengths
   * Axis ratio (shape descriptor)

