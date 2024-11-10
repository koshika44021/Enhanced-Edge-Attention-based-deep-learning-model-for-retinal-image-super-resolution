EEASRCNN: Edge-Enhanced Attention-Based Super-Resolution Convolutional Neural Network for Ocular Disease Detection
EEASRCNN is a novel deep learning architecture designed to enhance the quality of retinal images for improved diagnosis of ocular diseases, including cataracts, glaucoma, and various retinal pathologies. This project focuses on super-resolution techniques tailored to the medical imaging field, addressing challenges such as low image resolution, noise, and poor illumination in retinal images.

Project Overview
In medical diagnostics, high-resolution images are essential for detecting fine details like blood vessels and optic disc structures, which play a crucial role in identifying early signs of ocular diseases. However, many retinal images, especially those from telemedicine sources, are of suboptimal quality. EEASRCNN aims to overcome these limitations by introducing an advanced super-resolution model that improves image clarity and sharpness, enabling better diagnostic accuracy.

Key Features
Custom Edge Loss Function: Enhances the preservation of edge details, critical for accurately capturing blood vessels and other small structures.
Sharpening Layer: Improves the clarity and contrast of the output image, making fine details more visible.
Attention Mechanisms: Integrates both channel and spatial attention to refine feature extraction, focusing on the most informative regions within the image.
Custom Retinal Dataset: Includes high-resolution and low-resolution images of various ocular conditions, supporting robust training and evaluation of the model.
Model Performance
The EEASRCNN model is evaluated using standard image quality metrics, including Peak Signal-to-Noise Ratio (PSNR) and Structural Similarity Index (SSIM). Results show a significant improvement in the visual quality of retinal images, with sharper edges and clearer structural details compared to baseline super-resolution models. These enhancements support better clinical interpretation, aiding in the early detection and diagnosis of ocular diseases.

Repository Contents
Model Architecture: Code for the EEASRCNN architecture, including custom layers, loss functions, and attention modules.
Dataset Preparation: Scripts for processing and loading the custom retinal image dataset.
Training and Evaluation: Notebooks and scripts for training the model and evaluating performance on test data.
Results and Visualizations: Sample outputs and metrics demonstrating the model's effectiveness in enhancing retinal image quality.
Getting Started
Clone the repository and install the required dependencies.
Prepare the dataset using the provided scripts or load your own retinal images.
Train the model or load pre-trained weights for immediate evaluation.
Visualize and assess the super-resolved images for diagnostic applications.
Applications
This project demonstrates how deep learning can transform retinal image analysis by improving image resolution and detail. EEASRCNN is highly relevant for applications in telemedicine and automated disease detection, offering a pathway to enhance diagnostic capabilities in resource-constrained environments.
