# Vehicle Object Detection

## Description
This project involves using a Faster R-CNN model with a ResNet-50 backbone pre-trained on the COCO dataset for vehicle object detection. The model is fine-tuned on a custom vehicle dataset to detect different classes including background, car, truck, and pedestrian. The project also includes training and evaluation using GPU resources from Kaggle.

## Model
- **Model:** Faster R-CNN with ResNet-50 backbone
- **Pre-trained Weights:** COCO_V1 weights from torchvision models
- **Fine-tuning:** The model is fine-tuned on a custom vehicle dataset

## Dataset
- **Dataset:** Custom vehicle dataset
  - **Classes:** Background, car, truck, pedestrian
  - **Annotation Format:** COCO format

## Implementation Details
- **Inference:**
  - Perform inference using the pre-trained Faster R-CNN model with COCO_V1 weights.
  - Visualize the detection results on sample images.
- **Fine-tuning:**
  - Fine-tune the Faster R-CNN model on the custom vehicle dataset using Kaggle's T4 x2 GPU resources.
  - Monitor and plot the training loss.
  - Visualize the detection results on the custom dataset images.

## Usage
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/CV-Projects.git
   cd CV-Projects/Vehicle-Object-Detection
