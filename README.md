# Image-Segmentation

• Transformed a pretrained MobileNetv2 backbone, initially designed for ImageNet classification, into an FCN by replacing
the final fully connected (FC) layers with convolutional layers, enabling it to handle variable-sized inputs and perform
dense pixel-wise predictions.
• Conducted a comparative analysis of pixel-wise accuracy and mean IOU accuracy against the FCN ResNet50 model.
• Implemented the N-Cut algorithm to perform image segmentation, resulting in the partitioning of images into two
distinct segments
