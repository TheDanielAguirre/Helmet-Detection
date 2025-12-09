# Technical Approach

## Model Architecture: AlexNet
AlexNet is a convolutional neural network made of:
- **Convolutional layers** for feature extraction  
- **ReLU activation** for nonlinearity  
- **Max-pooling** for downsampling  
- **Dropout** for regularization  
- **Fully connected layers** for final classification  

The final layer outputs **two classes**:
- Helmet
- No Helmet

## Input Processing
- All images resized to **224×224**
- Normalized using ImageNet mean/std
- Optional: grayscale mode for experimentation
- Augmentation used: flips, rotations, jitter

## Training Setup
- Loss function: **CrossEntropy**
- Optimizers tested: **Adam**, **SGD**
- Hyperparameters tested:
  - Batch sizes: 16 vs 64
  - Learning rates: 0.001 vs 0.0001
  - Augmentation: ON vs OFF
- Trained for **8 epochs**
- Logged using **Weights & Biases**

## Architecture Comparison
We compared:
- **AlexNet**
- **ResNet18**

ResNet18 performed best, reaching **95% accuracy**.

---

[⬅ Back to Home](index) | [📊 Results & Visualizations](results)
