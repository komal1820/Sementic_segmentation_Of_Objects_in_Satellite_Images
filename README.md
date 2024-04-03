# Sementic_segmentation_Of_Objects_in_Satellite_Images

This project tackles the challenge of semantic segmentation in satellite imagery, aiming to precisely identify and classify objects like roads, buildings, vegetation, water bodies, and crops. It proposes a modified U-Net architecture that leverages the Inception ResNet V2 encoder for improved performance.

# Key Features:

• Modified U-Net architecture with Inception ResNet V2 encoder

• Pixel-level classification for five classes: roads, buildings, vegetation, water, and crops

• High accuracy: 82% Dice coefficient and 87% pixel accuracy on the validation set

• Dataset augmentation (shift, scale, rotate) to enhance training data diversity

# Technology Used:

**Deep Learning:** This project utilizes deep learning techniques, specifically a convolutional neural network (CNN) architecture, to perform semantic segmentation on satellite images.

**U-Net Architecture:** The core model is a modified U-Net, a well-established CNN architecture designed for image segmentation tasks. It excels at preserving spatial information while capturing high-level features.

<img width="735" alt="Screenshot 2024-04-03 at 7 45 04 PM" src="https://github.com/komal1820/Sementic_segmentation_Of_Objects_in_Satellite_Images/assets/69956556/647c61e6-70d9-4f85-8e7c-74d6a8073c8d">


**Inception ResNet V2 Encoder:** The modified U-Net employs the Inception ResNet V2 encoder for feature extraction. This encoder enhances the model's mathematical and structural complexity, leading to improved segmentation accuracy.

![1*CYRgf1i1q_4hx5AcdcaSEg](https://github.com/komal1820/Sementic_segmentation_Of_Objects_in_Satellite_Images/assets/69956556/97b7fd39-7638-4de6-8691-4f5bd69426d6)


**Image Augmentation:** The project incorporates data augmentation techniques (shifting, scaling, rotating) to artificially expand the training dataset and increase its diversity. This helps the model generalize better to unseen data.

# Result Analysis:

<img width="730" alt="Screenshot 2024-04-03 at 7 43 26 PM" src="https://github.com/komal1820/Sementic_segmentation_Of_Objects_in_Satellite_Images/assets/69956556/43cfc31f-e6f5-4d70-9714-68ce4cfb31d6">

# Dataset

https://humansintheloop.org/resources/datasets/semantic-segmentation-dataset/

# Published Paper:

This project is based on a published paper. You can find the paper at [https://ieeexplore.ieee.org/document/9864504](url).

