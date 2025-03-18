## Fabric Texture Analysis using First-Order and Second-Order Features

Project Overview

This project aims to analyze fabric textures by extracting first-order statistical features (histogram-based) and second-order features (GLCM - Gray-Level Co-Occurrence Matrix). The comparison between smooth and textured fabric is visualized using histograms and bar charts.

Features Extracted

First-Order Features

Mean - Average intensity of pixel values.

Variance - Distribution of pixel intensity values.

Skewness - Asymmetry in pixel intensity distribution.

Entropy - Measure of randomness in texture.

Second-Order Features (GLCM-based)

Contrast - Measures intensity variation between adjacent pixels.

Correlation - Measures the relationship between neighboring pixels.

Energy - Indicates the uniformity of texture.

Homogeneity - Measures the similarity of pixel values.

Technologies Used

Python (3.11.9)

OpenCV (cv2)

NumPy

Matplotlib

Scikit-Image (skimage.feature)

How It Works

Convert images to grayscale.

Extract first-order statistical features from pixel intensity values.

Compute GLCM and extract second-order texture features.

Visualize results with:

Histogram for pixel intensity distribution.

Bar chart comparing feature values for different fabric types.

Installation & Usage

Clone this repository:

git clone https://github.com/yourusername/fabric-texture-analysis.git
cd fabric-texture-analysis

Install dependencies:

pip install numpy opencv-python matplotlib scikit-image

Run the script:

python fabric_texture_analysis.py

Sample Output

Histogram Example



Feature Comparison Bar Chart



Use Case

Textile Industry: Quality control based on texture properties.

Computer Vision: Automated texture classification.

Medical Imaging: Analysis of patterns in X-rays or MRI scans.

Author

Ahmad Bidni Musyafa
