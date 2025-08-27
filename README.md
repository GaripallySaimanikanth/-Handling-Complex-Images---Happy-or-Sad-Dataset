# -Handling-Complex-Images---Happy-or-Sad-Dataset
Developed a CNN model on the Happy or Sad dataset to classify facial expressions with 99.9% accuracy. Applied image preprocessing and augmentation to handle small, complex data. Implemented early stopping and dropout to prevent overfitting, gaining hands-on experience in deep learning and model optimization.
Handling Complex Images – Happy or Sad Dataset
📌 Project Overview
This project focuses on building a Convolutional Neural Network (CNN) to classify images of emoji-like faces as Happy 😃 or Sad 😢. The dataset consists of 80 images (40 happy, 40 sad). The main objective was to achieve ≥99.9% training accuracy while ensuring efficient training with early stopping.
🎯 Objectives
Develop a deep learning model to classify complex facial images.
Apply image preprocessing and augmentation to improve generalization.
Implement early stopping once accuracy reached 99.9%.
Explore CNN architectures using TensorFlow/Keras.
🛠️ Tech Stack
Language: Python
Libraries: TensorFlow, Keras, NumPy, Matplotlib, Seaborn
Tools: Jupyter Notebook / Google Colab
📂 Dataset
Total Images: 80 (40 Happy, 40 Sad)
Images were resized and normalized before being fed into the CNN.
Augmentation: rotations, zooms, flips, and shifts were applied to expand the dataset.
⚙️ Approach
Data Preprocessing: Normalization and augmentation.
CNN Model Architecture:
Convolutional + Pooling layers for feature extraction.
Dense layers with ReLU activation.
Dropout layers to prevent overfitting.
Softmax classifier for binary classification.
Training:
Early stopping callback triggered at 99.9% accuracy.
Hyperparameter tuning for optimizer, learning rate, and batch size.
📊 Results
Achieved 99.9%+ accuracy in training within a few epochs.
Robust performance on test images.
Demonstrated effective handling of small, complex image datasets.
🚀 Key Learnings
Designing CNNs for image classification tasks.
Importance of augmentation for small datasets.
Effective use of callbacks to optimize training.
Hands-on experience with TensorFlow/Keras workflows.
