# YOLOv4 Custom Training

## Overview  
This notebook provides a detailed workflow to train the Scaled YOLOv4 object detection model on a custom dataset. It clones the ScaledYOLOv4 repository, installs necessary dependencies, downloads a dataset from Roboflow, and runs model training with tensorboard integration for monitoring performance.

## Features  
- Clone and setup the ScaledYOLOv4 repository  
- Install custom CUDA Mish activation function  
- Download and prepare custom dataset via Roboflow  
- Train YOLOv4 model on custom data for 25 epochs  
- Visualize training results with tensorboard and image outputs  
- Display ground truth and augmented training data examples  

## Tech Stack  
- Python  
- Jupyter Notebook / Google Colab  
- PyTorch  
- Roboflow Python SDK  
- YAML  
- TensorBoard  

## How to Use  
1. Open this notebook in Google Colab or Jupyter environment.  
2. Run each cell sequentially to clone repositories, install dependencies, and load dataset.  
3. Train the model by running the training cell.  
4. Launch tensorboard to monitor training metrics.  
5. Review generated results images and training data samples.  

## Status  
This notebook is organized and ready for GitHub presentation, providing a clear, reproducible workflow for custom YOLOv4 training.