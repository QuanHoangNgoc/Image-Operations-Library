# 🎨 Image Operations Library

**Author:** Quan Hoang Ngoc  
**Purpose:** Contributing for Learning and Sharing  
**Term:** HK2, 2024

---

## 🌟 About

Welcome to the **Image Operations Library**! This comprehensive toolkit is designed to simplify and enhance your image processing tasks. Whether you need to manipulate, analyze, or transform images, our library offers a rich set of functionalities to meet your needs.

---

## 🗂️ Repository Structure

- **LIB:** Contains the core development modules and progress related to the image processing library.

---

## 📚 Guideline Documentation

### **Imops Class**

#### 🔧 Initialization Parameters
- `__init__(mode, image_size, scale_const)`: Initializes the image processing environment with specified parameters.

#### 🖼️ Image Loading
- `load_image_from_file()`: Load an image with the following methods:
  - `read_image()`: Load images in **RGB** or **GRAY (WB)** mode.
  - `resize_image()`: Resize images to specified dimensions.
  - `scale_image()`: Scale images according to a defined constant.

#### 📊 Image Display
- `plot_image()`: Visualize images with customizable parameters.

#### 🌗 RGB to GRAY Conversion
- `rgb2wb()`: Convert RGB images to grayscale.

#### 📈 Histogram Operations
- `plot_histogram_of_image()`: Generate and display histograms for image analysis.

#### 🧮 Image Similarity
- `compute_distance_similar()`: Calculate similarity distances between images.

#### 🛠️ Feature Extraction
- `extract_histogram_from_image()`: Extract and analyze image histograms.
- `extract_sobel_feature_from_image()`: Extract edge features using Sobel filters.
- `extract_hog_feature_from_image()`: Extract Histogram of Oriented Gradients (HOG) features.

#### 🔄 Image-to-Image Operations
- `sobel_image_from_image()`: Apply Sobel filtering to generate edge-detected images.
- `hog_image_from_image()`: Generate HOG images for feature representation.
- `equalize_image()`: Perform adaptive histogram equalization to enhance image quality.

### **FileOps Class**

#### 🗄️ List Files
- `list_files_from_root_folder()`: Retrieve all file paths, including folder and file names from the root directory.

---

## ⚙️ Installation Guide

To integrate our library into your project:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/Image_Ops_Lib.git
   cd Image_Ops_Lib/LIB
   ```

2. **Import the Library:**
   Start using the library's functionalities by importing `lib.py` into your project:
   ```python
   from lib import Imops, FileOps
   ```

---

## 💖 Support and Donation

Your support is essential for the continuous development of this library:

- **Star the Repository:** If you find this project useful, please give it a star to show your appreciation.
- **Community Contribution:** We are committed to sharing knowledge and contributing to the community with dedication and enthusiasm.

Thank you for your support!

---
