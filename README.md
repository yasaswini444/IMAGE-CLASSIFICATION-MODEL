# IMAGE-CLASSIFICATION-MODEL
*COMPANY* : CODTECH IT SOLUTIONS 
*NAME*: GUNNA PAVAN 
*INTERN ID*: CT04DN1757 
*DOMAIN* : MACHINE LEARNING 
*DURATION* : 4 WEEKS 
*MENTOR* : NEELA SANTOSH
*Objective*
To classify images into predefined categories using a Convolutional Neural Network (CNN) built with TensorFlow.
*What is CNN?*
A Convolutional Neural Network (CNN) is a deep learning architecture specially designed for processing structured arrays like images. It automatically detects important features such as edges, textures, and patterns without manual feature extraction.
*Framework Used*
TensorFlow (with Keras API)
Matplotlib (for visualization)
Dataset: CIFAR-10 (10 classes of 32x32 RGB images)
*Key Steps in Implementation*
Import Libraries
Load and Preprocess Data
Load CIFAR-10 dataset.
Normalize pixel values (0–255 → 0–1)
Build CNN Model
A typical CNN includes:
Convolutional layers (Conv2D)
Pooling layers (MaxPooling2D)
Dense layers (for final classification)
Compile the Model
Loss Function: Sparse Categorical Crossentropy
Optimizer: Adam
Metrics: Accuracy
Train the Model
Fit the model on training data.
Validate on test data.
Evaluate Performance
Check test accuracy.
Plot training vs. validation accuracy.
*Output*
Accuracy metrics after each epoch
Final test accuracy (e.g., ~70-80% on CIFAR-10)
Training/validation accuracy graph
Deliverables
Functional .py script (cnn_image_classification.py)
Ready to run on any machine with TensorFlow installed
Can be extended to other image datasets
![Image](https://github.com/user-attachments/assets/21446e6a-3779-410d-b607-4f3207371c6a)
