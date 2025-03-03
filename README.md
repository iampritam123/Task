# Task

**STEPS FOR SEPARATING THE CENTER ARE FROM THE IMAGE**


**Load the Image** – Read the input image using OpenCV and verify successful loading.

**Convert Color Formats** – Convert the image from BGR to RGB for visualization and grayscale for processing.

**Apply Thresholding** – Use binary inverse thresholding to distinguish the foreground object from the background.

**Find Contours **– Detect contours from the thresholded image and select the largest one, assuming it represents the main object.

**Define GrabCut Mask** – Initialize a mask and create background and foreground models for GrabCut.

**Apply GrabCut** – Use the bounding rectangle of the largest contour to perform GrabCut segmentation.

**Refine the Segmentation** – Modify the mask to retain only the segmented object while removing the background.

**Extract and Display the Center Area** – Apply the refined mask to isolate the center area and visualize both the original and segmented images using Matplotlib.
