- this is all development progress of this module.
# Guideline docs: 
*** Imops class ***
### init(mode, image_size, scale_const) to config for load image
### load image use:
 - load_image_from_file()
   - read_image(): the image that read will be **RGB mode or GRAY(WB) mode** 
   - resize_image()
   - scale_image()
### show image use: 
- plot_image()
### convert from RGB to GRAY mode use:
- rgb2wb()
### plot histogram use:
- plot_histogram_of_image() 
### compute distance simular between 2 img matrixs use:
- compute_distance_simular() 
### extract feature types from image use:
- extract_histogram_from_image()
- extract_sobel_feature_from_image()
- extract_hog_feature_from_image()
### im2im ops use: 
- solbel_image_from_image()
- hog_image_from_image()
- equalize_image()

*** FileOps class *** 
### list all file paths with folder and file name use: 
- list_files_from_root_folder()
