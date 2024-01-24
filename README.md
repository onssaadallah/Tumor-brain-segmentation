# Tumor-brain-segmentation
This project aims to automate brain tumor segmentation in MRI images using Mask R-CNN, an instance segmentation algorithm. The objective is to identify and delineate tumor regions within the brain accurately.
Tumor brain segmentation follows these steps:
1. Collect and preprocess the images, annotating tumor regions to create a labeled dataset.
2. Choose Mask R-CNN for instance segmentation and initialize the model with pre-trained weights from COCO.
3. Train the model, optimizing for bounding box regression and mask segmentation.
4. Evaluate the model's performance on a validation set and validate it on a separate testing set.
5. Refine the segmentation results and verify accuracy through image visualization.

