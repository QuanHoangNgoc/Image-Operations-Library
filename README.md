---

# 🌟 Image Operations Library

**Author:** Quan Hoang Ngoc  
**Purpose:** Contributing for Learning and Sharing  
**Term:** HK2, 2024

## What is it?

The **Image Operations Library** is a powerful toolkit designed to provide developers with essential image processing capabilities. From loading and manipulating images to advanced feature extraction and image transformations, this library is your go-to solution for enhancing and analyzing images in various applications.

## Why do we do it?

In the ever-evolving world of image processing, having a reliable and versatile toolset is crucial. This library was developed to fill the gap between simple image manipulation and advanced feature extraction, making complex image operations accessible to developers and researchers alike. Whether you're working on computer vision projects, data analysis, or just exploring image processing, this library provides the functionality needed to streamline your workflow.

## Who is it for?

This library is ideal for developers, data scientists, and researchers who require robust image processing tools. It's designed to be both user-friendly for beginners and flexible enough for advanced users. Some practical examples and demos, including edge detection and histogram balancing, demonstrate the library's capabilities, making it easier to understand and apply in real-world scenarios.

- **Demo Video:** [Watch on YouTube](https://youtu.be/EcjI4TKktR4?feature=shared)
- **Kaggle Notebook:** [Explore imlib Demo](https://www.kaggle.com/code/quanhoangngoc/imlib/notebook)

## How did we do it?

### Detailed Approach:

1. **Core Functionalities:**
   - **Load Image from File:** Supports reading, resizing, scaling, and converting image modes for various image types.
   - **Compute and Plot Information:** Allows visualization of images, histogram generation, and calculation of similarity distances between image matrices.
   - **Feature Extraction:** Provides tools to extract key features like histograms, Sobel sums, and Histogram of Oriented Gradients (HOG) from images.
   - **Image-to-Image (im2im) Transformations:** Enables transformations such as Sobel filtering, HOG image generation, and adaptive histogram equalization.

2. **Project Structure:**
   - **LIB Directory:** Contains the core module (`lib.py`) that drives all functionalities.
   - **Three Core Classes:**
     - **ut:** For messaging, notes, and debugging support.
     - **Imops:** The main class for all image processing functions.
     - **FileOps:** Facilitates file operations like listing files in the root directory.

### Frameworks and Tools Used:

- **Python:** The core programming language for developing the library due to its extensive support for image processing and machine learning.
- **OpenCV:** Used for basic image processing tasks like reading and writing images, applying filters, and transformations.
- **Matplotlib & Seaborn:** Utilized for plotting and visualizing image data, histograms, and other statistical information.
- **Scikit-image:** Provides advanced image processing features, such as HOG feature extraction and histogram equalization.
- **Numpy:** Used for matrix operations and handling image data efficiently.

These tools were chosen for their robustness, ease of use, and extensive community support, making them ideal for developing a comprehensive image processing library.

## What did you learn?

Throughout this project, we gained deeper insights into the challenges of image processing, especially in areas like feature extraction and image transformation. We also learned the importance of balancing ease of use with functionality to create a library that serves both beginners and experts.

## Achievements

- **High-Quality Image Processing:** The library successfully integrates various image processing techniques into a single, easy-to-use package.
- **Comprehensive Documentation:** Demos and examples provided make it easy to understand and apply the library's features.
- **Community Contribution:** By sharing this library, we hope to contribute to the learning and development of others in the field of image processing.

## How to Install and Run the Project

### Installation Guide:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/Image_Ops_Lib.git
   cd Image_Ops_Lib/LIB
   ```

2. **Install Required Packages:**
   Ensure you have Python installed, then install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. **Import and Use the Library:**
   Start using the library's functionalities by importing `lib.py` into your project:
   ```python
   from lib import Imops, FileOps
   ```

### Usage Example:

```python
from lib import Imops

# Initialize the Imops class
im_ops = Imops()

# Load and process an image
image = im_ops.load_image('example.jpg')
edges = im_ops.sobel_filter(image)
im_ops.plot_image(edges, title="Sobel Edge Detection")
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

