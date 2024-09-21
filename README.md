
# 🌟 Image Classification Using CNN with CIFAR-10 Dataset 🌟

## Overview
This project involves building an image classification model using Convolutional Neural Networks (CNN) with the CIFAR-10 dataset. The goal is to classify images into 10 categories:

🛩️ airplanes, 🚗 automobiles, 🐦 birds, 🐱 cats, 🦌 deer, 🐶 dogs, 🐸 frogs, 🐴 horses, 🚢 ships, and 🚚 trucks.

## Project Highlights

### 1. Data Loading and Preprocessing:
- 📂 Loaded the CIFAR-10 dataset.
- 🔍 Normalized pixel values to the [0, 1] range.
- 🏷️ Defined class names for easy reference.

### 2. Model Architecture:
- 🛠️ Built a custom CNN model using TensorFlow and Keras.
- 📏 Model layers used:
  - `Conv2D`, `MaxPooling2D`, `Flatten`, `Dense`.
- 🧩 Compiled the model using:
  - **Optimizer**: Adam
  - **Loss function**: SparseCategoricalCrossentropy

### 3. Training and Evaluation:
- 🏋️‍♂️ Trained the model for **10 epochs**.
- 📈 Achieved:
  - **Training accuracy**: 78.74%
  - **Validation accuracy**: 70.67%
- 🧪 Evaluated model performance on test data.

### 4. Hyperparameter Tuning:
- 🛠️ Used **Keras Tuner** for hyperparameter optimization.
- 🔧 Tuned parameters like:
  - Number of units in `Conv2D` layers
  - Learning rate
  - Dropout rate
- 🏆 Improved model performance through tuning.

## Key Learnings:
- **Data Visualization**: 📊 Visualized training images and analyzed model predictions.
- **Model Performance**: 🚀 Importance of hyperparameter tuning to enhance accuracy.
- **Deep Learning Tools**: 💡 Hands-on experience with TensorFlow, Keras, and Keras Tuner.

## 📊 Results:
- **Initial Model Accuracy**: ~78.74%
- **Post Hyperparameter Tuning**: Notable improvements in validation accuracy.
