# 🎨 Image Operations Library

- **Quan Hoang Ngoc**
- Contribute for Learning and Sharing 
- _HK2_, 2024

![icon](https://example.com/icon.png) <!-- Replace with your icon URL -->

### About 
Welcome to the Image Operations Library, a comprehensive toolkit designed to streamline image processing tasks. Our library includes a rich set of functionalities to manipulate, analyze, and transform images effectively.

### Repository Structure 
- **LIB:** This section encompasses all the developmental progress made within this module.

# Guideline Docs

## Imops Class
### Initialization Parameters
- `__init__(mode, image_size, scale_const)`: Configures image loading parameters.

### Image Loading
- `load_image_from_file()`
  - `read_image()`: Loads images in **RGB mode or GRAY (WB) mode**.
  - `resize_image()`
  - `scale_image()`

### Image Display
- `plot_image()`

### RGB to GRAY Conversion
- `rgb2wb()`

### Histogram Operations
- `plot_histogram_of_image()`

### Image Similarity
- `compute_distance_similar()`

### Feature Extraction
- `extract_histogram_from_image()`
- `extract_sobel_feature_from_image()`
- `extract_hog_feature_from_image()`

### Image-to-Image Operations
- `sobel_image_from_image()`
- `hog_image_from_image()`
- `equalize_image()`

## FileOps Class
### List Files
- `list_files_from_root_folder()`: Retrieves all file paths including folder and file names.

### Installation Guide 
To integrate our library into your projects:
- Clone the `LIB` branch of this repository.
- Import `lib.py` to start using the library's extensive functionalities.

### Support and Donation 
Your support motivates us to continually enhance our library:
- If you find this project useful, please star it to show your appreciation.
- We are committed to sharing knowledge and contributing to the community with dedication and enthusiasm. Thank you for your support!
