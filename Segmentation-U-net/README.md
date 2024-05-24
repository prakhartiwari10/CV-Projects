# Segmentation using U-Net

## Description
This project involves implementing a U-Net architecture for semantic segmentation tasks.
The model is trained on a Dogs and Cats dataset with annotation masks to segment the images into dog and cat regions.

## Dataset
- **Dataset:** Dogs and Cats dataset with annotation masks.
- **Description:** The dataset consists of images of dogs and cats along with corresponding annotation masks.

## U-Net Architecture
- **Description:** U-Net is a convolutional neural network architecture designed for semantic segmentation tasks. It consists of a contracting path to capture context and a symmetric expanding path to enable precise localization.

## Implementation Details
- **Model:** U-Net model implemented from the original U-Net paper.
- **Training:** The model is trained on the Dogs and Cats dataset with annotation masks.
- **Loss Function:** Binary cross-entropy loss is used as the loss function.
- **Optimizer:** Adam optimizer is used for training the model.
- **Learning Rate Scheduler:** Learning rate is decayed over epochs for better convergence.

## Usage
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/CV-Projects.git
   cd CV-Projects/Segmentation-U-net
