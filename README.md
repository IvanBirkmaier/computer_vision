# Image Classification with VGG19

## Project Description
This project trains a neural network to classify images from the Open Images Dataset into three categories: Alpaca, Camel, and Dog.

### Key Components
- **Dataset**: [Open Images Dataset](https://storage.googleapis.com/openimages/web/visualizer/index.html?type=detection)
- **Base Model**: VGG19 pretrained on ImageNet
- **Tasks**:
  - Split dataset into 80/20 train/test
  - Transfer Learning: Train and evaluate the VGG19 model
  - Data Augmentation: Use random flip, contrast, and translation; compare results
  - Architecture Modification: Enhance VGG19 with inception and conv layers, freeze initial layers, and test with custom images

### Evaluation
- **Metrics**: Accuracy on train vs. test set, infrastructure, inference time, number of parameters, and confusion matrix for category confusion
- **Comparison**: Analyze results from different experiments

## Tech Stack
- **Python**
- **TensorFlow & Keras**
- **FiftyOne**
- **Matplotlib**
- **NumPy**
- **PIL (Python Imaging Library)**
- **IPython.display**

